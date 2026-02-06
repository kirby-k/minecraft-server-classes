Classes for minecraft server

# Usage

1. Navigate to your Minecraft server directory
2. Create the path where the `Skript` files will live:
    - They can live in any directory under `scripts/`, but I chose to name it `classes`

```sh
mkdir -p `plugins/Skript/scripts/classes/`
```

3. Place all `*.sk` files in this directory
4. Run `sk reload all` as `op` on your server

## Note on Bounds

Bounds are messed up for some reason, to use bounds correctly you must:
1. Face north
2. Place first corner bound one block south of where you want the actual bound
3. Place second corner bound one block east of where you want the actual bound