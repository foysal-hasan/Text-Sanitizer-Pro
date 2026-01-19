# Text Sanitizer Pro - Chrome Extension

A Chrome Extension (Manifest V3) that sanitizes text by replacing restricted words with safe alternatives.

## Installation

1. Open Chrome and navigate to `chrome://extensions/`
2. Enable "Developer mode" (toggle in the top right)
3. Click "Load unpacked"
4. Select the folder containing the extension files

## Usage

1. Click the extension icon in your Chrome toolbar
2. Paste your text into the "Input Text" textarea
3. Click the "Sanitize" button
4. The sanitized output will appear in the "Sanitized Output" textarea
5. Click "Copy to Clipboard" to copy the sanitized text

## Adding New Words

To add custom word mappings:

1. Click the "Settings" section header to expand it
2. In the "Add New Word" form:
   - Enter the original word (e.g., "payment")
   - Enter the replacement (e.g., "pa_yment")
3. Click "Add Word"
4. The word will be saved and used for future sanitizations

## Managing Words

- **View all words**: Expand the Settings section to see all restricted words and their replacements
- **Delete a word**: Click the "Delete" button next to any word in the list

## Default Words

The extension comes with these default word mappings:

### Communication Triggers
- `email` → `ema_il`
- `gmail` → `gma_il`
- `whatsapp` → `wha_tsapp`
- `skype` → `sky_pe`
- `telegram` → `tele_gram`
- `discord` → `dis_cord`
- `phone` → `pho_ne`
- `mobile` → `mobi_le`
- `number` → `num_ber`
- `contact` → `conta_ct`
- `zoom` → `zo_om`
- `slack` → `sla_ck`
- `linkedin` → `linke_din`
- `facebook` → `face_book`
- `instagram` → `insta_gram`
- `twitter` → `twitt_er`
- `youtube` → `youtu_be`
- `tiktok` → `tik_tok`
- `snapchat` → `snapc_hat`
- `pinterest` → `pinter_est`
- `reddit` → `redd_it`
- `tumblr` → `tumb_lr`

### Payment Triggers
- `payment` → `pa_yment`
- `paypal` → `payp_al`
- `pay` → `p_ay`
- `payoneer` → `payon_eer`
- `crypto` → `cryp_to`
- `bitcoin` → `bitc_oin`
- `wire` → `w_ire`
- `bank` → `b_ank`
- `transfer` → `trans_fer`
- `cash` → `c_ash`
- `invoice` → `invo_ice`
- `outside` → `outs_ide`
- `direct` → `dir_ect`
- `stripe` → `str_ipe`

### Academic / Work Triggers
- `homework` → `homew_ork`
- `assignment` → `assig_nment`
- `essay` → `ess_ay`
- `thesis` → `the_sis`
- `exam` → `ex_am`
- `test` → `t_est`
- `degree` → `deg_ree`

### Reviews & Engagement
- `review` → `rev_iew`
- `feedback` → `feedb_ack`
- `rating` → `rat_ing`
- `trustpilot` → `trust_pilot`
- `followers` → `follow_ers`
- `subscribers` → `subscr_ibers`

### Marketing / Spam Triggers
- `guaranteed` → `guaran_teed`
- `money` → `mon_ey`
- `income` → `inco_me`
- `profit` → `prof_it`

## Features

- Case-insensitive word matching
- Preserves original case in replacements
- Dark/light mode support (follows system preferences)
- Word mappings synced across devices via Chrome sync
- Clean, modern UI

