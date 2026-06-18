# A Roll 20 Sheet for *Triangle Agency*
Welcome General Managers!  The files in this repo can be copied into your own Roll20 campaign to better faciliate your Agents' interface with the TTRPG Initiative in your region.

## Installation
1. Download all files within the Sheet folder.  This should include, at least, an `TriangleAgency.html` and `TriangleAgency.css` file.
2. On your Roll20 Campaign page, under Settings > Game Settings, set your 'Character Sheet Template' to 'Custom'.
3. Copy the contents of the HTML file into the 'HTML' tab of the sheet template, and the CSS file into the 'CSS' tab.
4. Click 'Save Changes' at the bottom of the page.  That's it!

## Instructions
The character sheet will remember entered text and selected options like any Roll20 sheet.

Click the buttons at the top of the sheet to switch to different sections of the sheet.

* **Main Info**: Contains the top-level info for your Agent: name, title, and importantly, level of access to the Frozen Yogurt Room.  It also houses a 'Roll' that Agents may use when Asking the Agency for help on a Mission.
* **Anomaly**: Contains info for the three Agency-approved Anomalous Abilities accorded to this Agent.  Click 'Add+' to add a new entry.  Click 'Modify' to reorganize or delete entries.  If your Agents collect more than 3 entries on this page, contact Human Resources for next steps.
* **Reality**: Contains records on Agency-vetted Relationships that assist with proper community integration.  Agents should keep these to a minimum.  Keeping this page blank is acceptable!
* **Competency**: Contains space for the many Requistions that your Agents will garner over the course of their careers!
* **Work/Life Balance**: An Agency timesheet used to demarcate Downtime spent between mission.  Each box is a checkbox that you may use to mark off progress along the Competency track, as well as any Time spent on the other tracks.  (If your Agents collect too much Time on other tracks, contact Human Resources for next steps.)

## Special Flags (Playwall Spoilers!)
These special Attributes may be manually added to your Agent's sheet to unlock extra behavior for the sheet.  To manually add an Attribute:
1. Open your Agent's sheet.  Navigate to the 'Attributes and Abilities' tab.
2. Click 'Add+' under Attributes to add a new Attribute.
3. For the name, use the exact text as instructed in the entry below.
4. For the 'Current' value, use 1.

<details>
  <summary>G3</summary>
  Assistant Director may receive access to the Sponsorship Die by adding the `sponsorroll` Attribute to their sheet.  This will replace the 'Roll' button functionality by automatically adding a d8 to the roll.  Simply ignore this die during any Agency-approved Anomalous Ability checks.  (Seeing the extra dice should provide extra incentive to other Agents to focus on their Competency tracks!)
</details>

<details>
  <summary>N1</summary>
  Niiiiice.  To give your Agent access to the 10-Sided Die, add the `used10` Attribute.  (That's "Use-d10", not "Used-10"; you get it.)  This will add a 'd10' button to the Main Info page.  Again, Agents should really be hammering this one.  
</details>

<details>
  <summary>U2</summary>
  Oh, good, you made it.  UNL3ASH support for the sheet can unlocked by manully adding an Attribute called `unleash`.  This will add an 'UNL3ASH' button to Main Info that will roll the Six-Sided Die.  Encourage your Agents to use this OFTEN.  'K, bye.  See you above.
</details>
