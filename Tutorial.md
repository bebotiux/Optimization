## Optimization Minecraft Guide

Guide for version 1.16+. Some things may still apply to 1.14 - 1.15.

## Intro

There will never be a guide that will give you perfect results. Each server has its own needs and limits on how much you can or are willing to sacrifice (ask customers). Playing with the options to fit the needs of your servers is what it is all about. This guide is only intended to help you get an idea of the basic parameters. You are free to modify them to the client's liking, always giving a good image of the company.

## Map pregenerate:

Map pregeneration is one of the most important steps in improving a minecraft server. You can use a plugin such as [Chunky](https://https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiqr5TGluvzAhWIlGoFHXwBDbUQFnoECAYQAQ&url=https%3A%2F%2Fwww.spigotmc.org%2Fresources%2Fchunky.81534%2F&usg=AOvVaw2RGi5NzonllW86cLD1zpaE) to pregenerate the world. Make sure to set up a world border so players don't generate new chunks! Note: pregenerate take alot of hours

# Configurations:

## server.properties

**network-compression-threshold**

`Good starting value: 256`

## Purpur.yml

**use-alternate-keepalive**

`value: true`

**dont-send-useless-entity-packets**

`value: true`

**aggressive-towards-villager-when-lagging**

`value: false`

**entities-can-use-portals**

`value: false`

**villager.brain-ticks**

`Good starting value: 2`

**villager.lobotomize**

`value: true`

**disable-treasure-searching**

`value: true`

**teleport-if-outside-border**

`value: true`

## Spigot.yml

**view-distance**

`Good starting value: 4`

**mob-spawn-range**

`Good starting value: 2`

**entity-activation-range**

`Good starting values:`

      animals: 16
      monsters: 22
      raiders: 36
      misc: 6
      water: 6
      villagers: 14
      flying-monsters: 35

**entity-tracking-range**

`Good starting values:`

      players: 48
      animals: 48
      monsters: 48
      misc: 32
      other: 64

**tick-inactive-villagers**

`value: false`

**nerf-spawner-mobs**

`value: true`

**merge-radius**

`Good starting values:`

      item: 3.5
      exp: 4.0

**hopper-transfer**

`Good starting value: 8`

**hopper-check**

`Good starting value: 8`

## Paper.yml

**no-tick-view-distance**

`Good starting value: 7`

**delay-chunk-unloads-by**

`Good starting value: 10`

**max-auto-save-chunks-per-tick**


`Good starting value: 8`

**prevent-moving-into-unloaded-chunks**

`value: true`

**entity-per-chunk-save-limit**

`Good starting values:`

      experience_orb: 16
      arrow: 16
      dragon_fireball: 3
      egg: 8
      ender_pearl: 8
      eye_of_ender: 8
      fireball: 8
      small_fireball: 8
      firework_rocket: 8
      potion: 8
      llama_spit: 3
      shulker_bullet: 8
      snowball: 8
      spectral_arrow: 16
      experience_bottle: 3
      trident: 16
      wither_skull: 4
      area_effect_cloud: 8
      
**seed-based-feature-search-loads-chunks**

`value: true`

**despawn-ranges**

`Good starting values:`

      soft: 30
      hard: 56
      
**per-player-mob-spawns**

`value: true`

**max-entity-collisions**

`Good starting value: 2`

**update-pathfinding-on-block-update**

`value: false`

**fix-climbing-bypassing-cramming-rule**

`value: true`

**armor-stands-tick**

`value: false`

**armor-stands-do-collision-entity-lookups**

`value: false`

**tick-rates**

`Good starting values:`

      sensor:
        villager:
          secondarypoisensor: 80
          nearestbedsensor: 80
          villagerbabiessensor: 40
          playersensor: 40
          nearestlivingentitysensor: 40
      behavior:
        villager:
          validatenearbypoi: 60
          acquirepoi: 120
          
**alt-item-despawn-rate**

`Good starting values:`

      enabled: true
      items:
          COBBLESTONE: 300
          NETHERRACK: 300
          SAND: 300
          RED_SAND: 300
          GRAVEL: 300
          DIRT: 300
          GRASS: 300
          PUMPKIN: 300
          MELON_SLICE: 300
          KELP: 300
          BAMBOO: 300
          SUGAR_CANE: 300
          TWISTING_VINES: 300
          WEEPING_VINES: 300
          OAK_LEAVES: 300
          SPRUCE_LEAVES: 300
          BIRCH_LEAVES: 300
          JUNGLE_LEAVES: 300
          ACACIA_LEAVES: 300
          DARK_OAK_LEAVES: 300
          CACTUS: 300
          DIORITE: 300
          GRANITE: 300
          ANDESITE: 300
          SCAFFOLDING: 600
          
**use-faster-eigencraft-redstone**

`value: true`

**disable-move-event**

`value: false`

**mob-spawner-tick-rate**

`Good starting value: 2`

**optimize-explosions**

`value: true`

**enable-treasure-maps**

`value: false`

**treasure-maps-return-already-discovered**

`value: true`

**grass-spread-tick-rate**

`Good starting value: 4`

**container-update-tick-rate**

`Good starting value: 1`

**non-player-arrow-despawn-rate**

`Good starting value: 15`

**creative-arrow-despawn-rate**

`Good starting value: 15`

**anti-xray**

`Depends on the buyer`

**remove-corrupt-tile-entities**

`value: true`

**nether-ceiling-void-damage-height**

`Good starting value: 127`

## Airplane.yml

**max-loads-per-projectile**

`Good starting value: 8`

**max-tick-freq**

`Good starting value: 25`

**activation-dist-mod**

`Good starting value: 7`

#### Bukkit.yml

**spawn-limits**

`Good starting values:`

    monsters: 20
    animals: 5
    water-animals: 2
    water-ambient: 2
    water-underground-creature: 3
    ambient: 1

**ticks-per**

`Good starting values:`

    monster-spawn: 10
    animal-spawns: 400
    water-spawns: 400
    water-ambient-spawns: 400
    water-underground-creature-spawns: 400
    ambient-spawns: 400
    
## Plugins

We recommend to use our plugins for your minecraft server, but we also recommend LaggAssist and ClearLagg

**Mob stacker plugins**

**Plugins enabling/disabling other plugins**
