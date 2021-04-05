# Midi adapter

Optional adapter to convert morse code into MIDI sound

## Installation

In order to use `Morseficator.Adapter.Midi` you have to install fluidsynth library.

On OSX: 
```
brew install fluidsynth
```

On Debian/Ubuntu:
```
sudo apt install libfluidsynth-dev
```

On Fedora:
```
sudo dnf install fluidsynth-devel
```

To install dependecies and run a REPL execute the following:
```
$ mix deps.get
$ iex -S mix
```