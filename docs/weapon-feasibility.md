# Weapon feasibility

**Status:** Initial planning baseline  
**Game data reviewed:** Local *Warhammer 40,000: Rogue Trader* blueprint data dated 23 July 2026

This document records an initial review of existing game foundations that may be reusable for Grey Knight weapons. It is exploratory, is not a technical specification, and does not commit the project to implementing any weapon.

## Summary

No complete Grey Knight-specific weapon from the backlog was found in the reviewed game blueprints. Several useful foundations already exist:

- Force swords, including Psy Rating interaction, attack VFX, and sound
- Space Marine and Astartes storm bolters
- Thunder hammer attacks and a Space Marine hammer
- Human psyker and Navigator staves
- Astartes flamers, heavy flamers, flame attack templates, VFX, and sound
- General heavy-weapon, burst-fire, and automatic-weapon systems

The in-game force sword named **Incinerator** is not the Grey Knight flame weapon. It is a distinct force sword and should not be used as evidence that a Grey Knight Incinerator already exists.

## Candidate assessment

| Weapon | Existing in game | Reusable foundation | Initial assessment |
| --- | --- | --- | --- |
| Nemesis Force Sword | No exact variant | Force sword mechanics, Psy Rating scaling, VFX, sound | Best first candidate |
| Nemesis Force Halberd | No | Two-handed melee and force-weapon systems | New model; grip and animation validation required |
| Nemesis Daemon Hammer | No exact variant | Thunder hammer attacks, knockback, Space Marine hammer | Strong early candidate |
| Nemesis Warding Stave | No | Psyker and Navigator staves, defensive buffs | Astartes rig and animation work required |
| Nemesis Falchion | No | One-handed sword systems | New model required |
| Dual Nemesis Falchions | No | General dual equipment and one-handed attacks | Likely requires bespoke paired animations |
| Grey Knight Storm Bolter | No exact variant | Astartes and Space Marine storm bolters, burst attacks | Strong early candidate; forearm mounting is the main challenge |
| Psycannon | No | Heavy and burst-fire weapon systems | New model, effects, and psychic behaviour required |
| Psilencer | No | Automatic fire and energy-effect systems | Substantial custom psychic projectile, VFX, and sound work |
| Incinerator | No exact variant | Astartes flamer, heavy flamer, flame templates and VFX | Strong early candidate |
| Heavy Psycannon | No | General heavy-weapon systems | Dreadknight-scale design makes infantry use uncertain |
| Heavy Incinerator | No | Heavy-flamer systems | Mechanics are reusable; scale and mounting are uncertain |
| Named/relic Nemesis weapons | No | Future Nemesis base weapons | Defer until base weapons are established |

The blueprint name **Falchion** found in the game data refers to Imperial Falchion-class spacecraft, not a Grey Knight melee weapon.

## Recommended investigation order

1. Nemesis Force Sword
2. Nemesis Daemon Hammer
3. Grey Knight Storm Bolter
4. Incinerator
5. Psycannon
6. Nemesis Force Halberd
7. Nemesis Warding Stave
8. Psilencer
9. Nemesis Falchion and Dual Nemesis Falchions
10. Heavy and named/relic variants

This order reflects expected reuse of existing game systems, not a final feature roadmap.

## Open implementation questions

- How Psy Rating should scale each weapon
- Whether all Nemesis weapons should use the existing force-weapon family
- Which Space Marine animations can be reused without visible clipping
- Whether the forearm-mounted storm bolter needs a custom equipment slot or rig attachment
- Which weapons need custom VFX, psychic effects, and sound
- Appropriate balance and acquisition rules
- Character and Adeptus Astartes restrictions
- Whether equipment should require the possible future **Origin: Grey Knight**

## Scope boundary

No weapon models, blueprints, balance values, or gameplay implementations are included at this stage. The next decision is which weapons, if any, should proceed to modelling and prototyping.
