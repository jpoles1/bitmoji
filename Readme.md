## List of bitmoji images:

* [here](https://api.bitmoji.com/content/templates)


## Making sense of the data

* Individual comics are in .imoji (1117 of them) replace the `%s` with an avatar id
* Multi-avatar comics are in .friends (296 of them) replace both `%s` with an avatar id (eg from .imoji or .friends)
* `https://render.bitstrips.com/v2/cpanel/:comic_id-%s-v1.png?option1&option2&...`
  * `transparent=1` to set the bg to true
  * `palette=1` no idea
  * `width=200` scale image width to 200 pixels
* `https://render.bitstrips.com/render/:comic_id/%s-v1.png?option1&option2&...`
  * `cropped=%22body%22` you can also set cropped to `"head"`
  * `outfit=971786` put the user in
  * `head_rotation=1` rotate the head to position 1
  * `body_rotation=1` rotate the body to position 1
  * `pd2={"mouth":"_blank"}` inside `pd2`, you can put any of these keys: `[  "beard",  "brow_L",  "brow_R",  "cranium",  "detail_E_L",  "detail_E_R",  "detail_L",  "detail_R",  "detail_T",  "ear_L",  "ear_R",  "eye_L",  "eye_R",  "eyelash_L",  "eyelash_R",  "eyelid_L",  "eyelid_R",  "eyelines_L",  "eyelines_R",  "forehead",  "glasses",  "hair_back",  "hair_front",  "hairbottom",  "hat",  "jaw",  "mouth",  "nose",  "pupil_L",  "pupil_R",  "stachin",  "stachout",  "tongue"]`