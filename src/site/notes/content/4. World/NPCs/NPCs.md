---
{"dg-publish":true,"permalink":"/content/4-world/np-cs/np-cs/"}
---




```meta-bind-button
label: New NPC
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/Template - NPC New.md"
    fileName: NewNPC
```


| NPC                                                                           | Pronounced | Art | Race                   | Gender | Pronouns | Sexuality | Age          | Occupation                                                                       | Alignment                          | Religion                                                                | Condition | Location                                                                                            | Associations                                                                                     | PartyRelationship |
| ----------------------------------------------------------------------------- | ---------- | --- | ---------------------- | ------ | -------- | --------- | ------------ | -------------------------------------------------------------------------------- | ---------------------------------- | ----------------------------------------------------------------------- | --------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ----------------- |
| [[content/4. World/NPCs/Aeloria Starwind\|Aeloria Starwind]]               | \-         | \-  | Half-Elf               | Female | \-       | \-        | \-           | Enchanter                                                                        | Chaotic Good                       | Sehanine Moonbow                                                        | Alive     | Elmswatch Enclave                                                                                   | The Moonlit Order                                                                                | Friendly          |
| [[content/4. World/NPCs/Calarel Qizumin\|Calarel Qizumin]]                 | \-         | \-  | [[Elf\|Elf]]           | Female | He/Him   | Asexual   | Mature Adult | [[6. Database/World-Building-main/Occupations/Government/summoner.md\|summoner]] | [[Lawful Neutral\|Lawful Neutral]] | \-                                                                      | Healthy   | <ul><li>[[content/4. World/Places/Calindor/Glitterfall/Glitterfall.md\\|Glitterfall]]</li></ul>     | \-                                                                                               | Friendly          |
| [[content/4. World/NPCs/Elara Oakheart\|Elara Oakheart]]                   | \-         | \-  | [[Half-Elf\|Half-Elf]] | Female | She/Her  | Bisexual  | Mature Adult | \-                                                                               | [[Chaotic Good\|Chaotic Good]]     | \-                                                                      | Healthy   | \-                                                                                                  | \-                                                                                               | \-                |
| [[content/4. World/NPCs/Elias\|Elias]]                                     | \-         | \-  | [[Human\|Human]]       | Male   | He/Him   | Straight  | Mature Adult | [[6. Database/World-Building-main/Occupations/Services/miller.md\|miller]]       | [[Neutral Good\|Neutral Good]]     | \-                                                                      | Healthy   | [[content/4. World/Places/Calindor/Borfaldor/Petalwood/Petalwood\|Petalwood]]                    | \-                                                                                               | Friendly          |
| [[content/4. World/NPCs/Elrohir Telrun\|Elrohir Telrun]]                   | \-         | \-  | Leonin                 | Male   | \-       | \-        | \-           | Sheriff of Petalwood                                                             | Lawful Neutral                     | Worships Solonor Thelandira                                             | Healthy   | Petalwood                                                                                           | The Dawn's Shadow, King's Guard                                                                  | Potential Ally    |
| [[content/4. World/NPCs/Elysandra Windwhisper\|Elysandra Windwhisper]]     | \-         | \-  | Elf                    | Female | \-       | \-        | \-           | Enchanter                                                                        | Chaotic Good                       | Follower of Corellon Larethian                                          | Healthy   | Enchanted Glade in the Forest of Whispers                                                           | The Circle of Enchanters                                                                         | Potential Ally    |
| [[content/4. World/NPCs/Elysia Windwhisper\|Elysia Windwhisper]]           | \-         | \-  | Half-Elf               | Female | \-       | \-        | \-           | Bard and Storyteller                                                             | Chaotic Good                       | Sehanine Moonbow                                                        | Healthy   | The Singing Woods Tavern                                                                            | The Whispering Lyre Performers                                                                   | Friendly          |
| [[content/4. World/NPCs/Finroth Tilvenar\|Finroth Tilvenar]]               | Fin-Roth   | \-  | [[Elf\|Elf]]           | Male   | He/Him   | Straight  | Mature Adult | \-                                                                               | [[Neutral Evil\|Neutral Evil]]     | [[content/4. World/Religion/Deities/elven-zandilar\|elven-zandilar]] | Healthy   | <ul><li>[[content/4. World/Places/Calindor/Borfaldor/Petalwood/Petalwood.md\\|Petalwood]]</li></ul> | [[content/4. World/Factions/Welcomers\|Welcomers]]                                            | Hostile           |
| [[content/4. World/NPCs/Thistledown Whisperwind\|Thistledown Whisperwind]] | \-         | \-  | [[pixie\|Pixie]]       | Female | She/Her  | Bisexual  | Adult        | [[baker\|baker]]                                                                 | [[Chaotic Good\|Chaotic Good]]     | \-                                                                      | Healthy   | [[content/4. World/Places/Calindor/Borfaldor/Petalwood/Petalwood\|Petalwood]]                    | [[content/4. World/Factions/The Whispering Court/The Whispering Court\|The Whispering Court]] | Friendly          |

{ .block-language-dataview}





````
~~~dataviewjs
let input = {
  "query": 'TABLE without id file.link as NPC, Pronounced, Art, Race, Gender, Pronouns, Sexuality, Age, Occupation, Alignment, Religion, Condition, Location, Groups as Associations, PartyStanding as PartyRelationship FROM "4. World" WHERE contains(Role, "NPC")',
  "filterColumnCount": 3,
  "markdownTable": false,
  "columnsWithoutFilters": ["NPC", "Pronounced", "Art", "Pronouns", "Sexuality", "Occupation", "Alignment", "Religion", "Associations", "PartyRelationship", "Location", "Age", "Race", "Gender", "Condition",],
  "filterCalloutColor": "blue",
  "its_cards": {
      "enabled": false,
      "columns": 3
  }
}
await dv.view("z_Templates/custom/filtering_dv", input) 
~~~
````


