# rmanbackup
Generic enough script for Oracle RMAN backups

This is essentially a collection of Oracle RMAN (receovery manager) scripts I used over time in most of the projects, where there was **no** specific need for a tailored solutions combined into a single script.
By tailored or specific solution I mean things like:
- section-based backups of big files
- multiple target disks for backups
- slow backup disks
- restrictive backup windows
- tape backups
  
todo make note of controlfile autobackup
todo make note of expected / normal scenario: DFs on a set of disks or ASM, FRA or a set of disks receives archlogs, separate set of disks for backup
