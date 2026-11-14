# PotionSkill (Paper 1.21.11)

Setiap player otomatis dapat 1 skill acak saat pertama join.
Tekan **Shift + F** untuk mengaktifkan skill (memberi beberapa potion effect), ada cooldown.

## Build
Butuh Java 21 + Maven:

    mvn clean package

Hasil: `target/PotionSkill-1.0.0.jar` -> taruh di folder `plugins/` server Paper 1.21.11.

## Perintah
- /pskill info            -> lihat skill kamu
- /pskill list            -> daftar semua skill
- /pskill set <player> <skill>  (admin)
- /pskill reroll [player]       (admin)
- /pskill reload                (admin)

Permission: `potionskill.use` (default semua), `potionskill.admin` (default op).
Edit skill, effect, durasi, level, dan cooldown di `plugins/PotionSkill/config.yml`.
