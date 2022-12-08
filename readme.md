# pyduofern-shutter-hacs

This repository is based on [@gulap's](https://github.com/gluap) amazing repositories [pyduofern-hacs](https://github.com/gluap/pyduofern-hacs) (release v0.3.2) and [pyduofern](https://github.com/gluap/pyduofern).

The primary focus of this fork is to enable 'timer' based control of [Rademacher](https://rademacher.de) Duo Fern window shutters/covers. Currently this option is 'hard coded' which means every movement command is executed as a 'time automatic' command. This allows e.g. movements with reduced motor speeds as long as the actors' 'time automatic' mode is enabled. In the current stage of this repository this 'time automatic' mode cannot be enabled by this hacs integration which means you'll have to set that option beforehand (e.g. via FHEM with DuoFern module) or manually (if you have e.g. a RolloTron Comfort).


## Disclaimer
> **Note**
> References within this repository to any specific company, products, processes, or services by trade name, trademark, manufacturer, or otherwise does not constitute an endorsement, recommendation, or favouring by any of the referenced subjects.
