# Distro Icons
This repo contains icons used for userflair on [old Reddit](http://old.reddit.com/r/unixporn) and emoji on [new Reddit](http://new.reddit.com/r/unixporn). It also contains the Naut CSS add-on used for userflair in the old design. To export the SVGs en masse for Reddit use the following command with `$size` as `96` (15px images) for old Reddit and `192` (30px images) for new Reddit:
```bash
for file in *.svg; do inkscape -d=$size $file -e ${file%svg}png; done
```
Original logo designs belong to their respective owners, stylised icons for r/unixporn licensed CC-BY-SA.
