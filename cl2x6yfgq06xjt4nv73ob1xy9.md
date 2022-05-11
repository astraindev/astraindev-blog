## How to Install Pygame on a Mac

[Pygame](https://www.pygame.org) is a gaming API written in, well, you guessed it, [Python](https://www.python.org). It lets you use the [Simple DirectMedia Layer](https://www.libsdl.org) (SDL 2) for all of your gaming needs.

## Pygame Prerequisites For The Mac

You will need the following installed on your Mac:

* [Homebrew](https://brew.sh)
* Python 3

To install Homebrew, issue the following command:

```zsh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

To install Python 3, issue the following command:

```
xcode-select --install
```

## Pygame Installation On The Mac

First, using Homebrew, install SDL 2:

```zsh
brew update  
brew install pkg-config xquartz 
brew install sdl2 sdl2_gfx sdl2_image sdl2_mixer sdl2_net sdl2_ttf
```

Create your virtual environment:

```zsh
python3 -m venv venv  
source venv/bin/activate  
```

Then update your pip:

```zsh
pip install —-upgrade pip setuptools  
```

And finally, install pygame:

```zsh
pip install wheel  
pip install venvdotapp  
venvdotapp 
pip install pygame  
```

## Testing The Pygame Install

The [Getting Started](https://www.pygame.org/wiki/GettingStarted) guide says to test it with:

```zsh
python -m pygame.examples.aliens  
```
---

It is a pretty fun game. If you like it, there is a game called [Solar Wolf](https://github.com/astraindev/solarwolf). It's a fast-paced shoot 'em up game.

Please let me know if you experience any issues.

What Pygame is your favorite? If you are a developer, what is your genre?