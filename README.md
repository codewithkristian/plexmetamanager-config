# Plex Meta Manager config

This is my Plex Meta Manager config, which adds a bunch of nice-to-have things to my Plex library. It's heavily based on [0x5f3's](https://github.com/0x5f3/pmm-config) config, with additional config for overlay support. 

This repo isn't well-documented (I would like to add that in the future), but considering that I learned a lot from reading other public configs on GitHub, I'm sharing this in case it helps.

<details>
<summary>Previous README details</summary>
This config will populate the following:

- Suggested (random, trending, popular, top-rated, most watched)
- Awards
- Year (top-rated)
- Decades (top-rated)
- Genre (popular)
- Genre (top-rated)
- Sub-genre (top-rated) *
- Seasonal *
- TMBD collections *

( * = movies only )

For more details on what each section contains: [movies](MOVIES.md) | [shows](SHOWS.md)
<br/>
<br/>
<br/>
**Install:**

clone into PMM's root directory:
```
git clone https://github.com/0x5f3/pmm-config config
```
initial run to populate collections:
```
python plex_meta_manager.py --config config/movie.yml --collections-only --run --ignore-schedules
python plex_meta_manager.py --config config/show.yml --collections-only --run --ignore-schedules
```
<br/>
After a sucessfull run, you should have something like this:
<br/>
<br/>
  
![shows](/assets/_/shows.jpg)
<br/>
  
![movies](/assets/_/movies.jpg)
</details>
