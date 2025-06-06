```
python inference/wan2.1_fun/predict_v2v.py \
    --config.data.data_rootdir="examples" \
    --config.experiment.run_seqs="boys-beach,animator-draw" \
    --config.experiment.save_path="outputs/wan-fun/examples" \
    --config.video_model.model_name="/export/share/projects/videogen/checkpoints/wan-fun/Wan2.1-Fun-1.3B-InP" \
    --config.video_model.transformer_path="/export/share/projects/videogen/checkpoints/wan-fun/Wan2.1-Fun-1.3B-InP/diffusion_pytorch_model.safetensors"
```