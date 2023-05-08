# Build MeidNote

## Virtual environment
    python3 -m venv .medinote
    source .medinote/bin/activate

## Clone repository
    git clone https://github.com/hikarimusic/MediNote.git
    cd MediNote
    pip install -r requirements.txt

## Build and view
    make html
    wslview _build/html/index.html