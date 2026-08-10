# Iron Nest Unofficial Fire Control Calculator

A quick web-based fire control calculator for [IRON NEST: Heavy Turret Simulator](https://store.steampowered.com/app/2950790), built because the in-game ballistic calculator can be slow to work through shot after shot.

**[Open the calculator](https://joeoakley52.github.io/UNOFFICIAL-Iron-Nest-FCC/)**

## What it does

- **Basic mode** — enter bearing, distance, and powder charges to get required elevation
- **Advanced mode** — adds target type, round type, time of flight, and target time, and calculates the exact clock time you need to fire
- **Firing Log** — save shots as you go, so you can reference past solutions
- **Charge preferences** — auto-select charges based on:
  - **Manual** — pick charges yourself
  - **Auto Low Angle** — lowest charge that stays under a max angle you set
  - **Economy** — lowest charge that lands the shot between 30°–50°
  - **Match History** — picks the charge closest to your average logged elevation
- Charges that would push elevation past the gun's 60° max are automatically skipped

## Notes

This is a **fan-made, unofficial tool** and is not affiliated with or endorsed by the IRON NEST development team. The formula used (`elevation = distance × 0.012 ÷ charges`) is based on community testing and matches current in-game behavior. If the developers change round physics or ballistics in a future update, the numbers here may need to be re-verified.

Made by: **Joe Oakley**
