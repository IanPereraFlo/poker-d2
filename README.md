# poker44-chunk-detector

Chunk-aggregate MLP detector for the Poker44 subnet.

A miner for Bittensor subnet 126 (Poker44). Loads a trained detector from `models/current.joblib` and scores incoming hand-chunk payloads.

## Run
```
bash scripts/run.sh
```

## Model
Trained on released Poker44 benchmark data; weights in `models/current.joblib` (sha in `model_manifest.json`).
