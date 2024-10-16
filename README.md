# Music-Generation-CVAE

## Generate polyphonic music in the style of classical piano using CVAE

## Pipeline
1. Collect music data (midi file format) of 2 composers: Beethoven and Bach
2. Preprocessing
    - Tempo standardization
    - Selection of 4/4 pieces
    - C major/minor transposition
    - Slicing to 8s per file
    - Label each file with 1 out of 4 emotions: happy, angry, sad and relax
3. Build CVAE model and train
4. Generate music

## Training evironment
- Google Colab
- GPU: T4
- Training duration: ~5 min / 400 epochs
