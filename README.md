# Transfer-Learning-Atari-Games

It can emulate any of the following games:
	
> ['Asterix', 'Asteroids',
> 'MsPacman', 'Kaboom', 'BankHeist', 'Kangaroo',
> 'Skiing', 'FishingDerby', 'Krull', 'Berzerk',
> 'Tutankham', 'Zaxxon', 'Venture', 'Riverraid',
> 'Centipede', 'Adventure', 'BeamRider', 'CrazyClimber',
> 'TimePilot', 'Carnival', 'Tennis', 'Seaquest',
> 'Bowling', 'SpaceInvaders', 'Freeway', 'YarsRevenge',
> 'RoadRunner', 'JourneyEscape', 'WizardOfWor',
> 'Gopher', 'Breakout', 'StarGunner', 'Atlantis',
> 'DoubleDunk', 'Hero', 'BattleZone', 'Solaris',
> 'UpNDown', 'Frostbite', 'KungFuMaster', 'Pooyan',
> 'Pitfall', 'MontezumaRevenge', 'PrivateEye',
> 'AirRaid', 'Amidar', 'Robotank', 'DemonAttack',
> 'Defender', 'NameThisGame', 'Phoenix', 'Gravitar',
> 'ElevatorAction', 'Pong', 'VideoPinball', 'IceHockey',
> 'Boxing', 'Assault', 'Alien', 'Qbert', 'Enduro',
> 'ChopperCommand', 'Jamesbond']

## Purpose
The ultimate goal of this project is to implement and compare various RL approaches with atari games as a common denominator.

## Usage

1. Clone the repo.
2. Go to the project's root folder.
3. Install required packages`pip install -r requirements.txt`.
4. Launch atari. I recommend starting with help command to see all available modes `python atari.py --help`.


### Model Architecture
Deep Convolutional Neural Network by [DeepMind](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)

## Know issues
1. When last tried Tensorflow didn't support 3.7.x, use 3.6 versions
