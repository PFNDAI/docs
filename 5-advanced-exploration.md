# Advanced Exploration

For advanced users, PATHFINDER AI offers customization options to enhance its performance. 
You can tweak noise thresholds in `config.yaml` to suit stars with high variability or retrain the deep learning model with custom TESS data via:

```bash
python train_model.py --data new_data.csv --epochs 50
```

Custom visualizations are achievable with:

```bash
python visualize.py --input output/results.csv --type folded
```

Fine-tuning Fourier analysis can target specific orbital periods by adjusting `fourier_settings.yaml`.
