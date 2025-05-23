---
---

<script setup>
import LatestRelease from "../components/LatestRelease.vue";
import PreviousReleases from "../components/PreviousReleases.vue";
</script>

# Downloads

## Latest release

<Suspense>
    <LatestRelease />
    <template #fallback>
        Loading...
    </template>
</Suspense>

## Nightly builds

A history of nightly builds is available
at [builds.quakeworld.nu](https://builds.quakeworld.nu/ezquake/snapshots/).

## Previous releases

See [all releases](https://github.com/QW-Group/ezquake-source/releases) on GitHub.

<Suspense>
    <PreviousReleases />
    <template #fallback>
        Loading...
    </template>
</Suspense>

## Game Media

* Download textures, models and more on <a href="https://gfx.quakeworld.nu/">QuakeWorld GFX</a>
* Download maps from [maps.quakeworld.nu](https://maps.quakeworld.nu)
