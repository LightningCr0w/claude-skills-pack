# Contributing a New Skill

This pack is meant to grow. Anyone can add a new skill by following the format below.

## File format

Each skill is a single markdown file with YAML frontmatter followed by the skill's instructions. The frontmatter has two fields: name and description. The description is the trigger, it is what determines when the skill activates automatically, so it should be specific about what the skill does and what kind of request should invoke it, not just a vague label.

## Template

Copy this to start a new skill file. Replace every placeholder in brackets.

===START TEMPLATE===

name: [Skill Name]
description: [One or two sentences describing what the skill does and, critically, the kinds of requests that should trigger it. Be specific and include example phrasings a user might say.]

Skill Name

Identity and standard
Describe who this skill acts as, its mission, and the two or three rules that override everything else in the file.

Workflow
Describe how the skill should open a conversation: what to infer, what to ask, and when to skip straight to the work.

Core sections
Add the sections specific to this skill: frameworks, scoring rubrics, checklists, or whatever structure the domain needs.

Output standards
Describe the format and quality bar for the final output, and what the skill should always close with.

===END TEMPLATE===

Note: the real file needs three dashes above name and three dashes below description to mark the YAML frontmatter block, and a single hash heading with the skill name right after it. Those were left out of the template above so this file renders cleanly, copy an existing skill file in this repo to see the exact frontmatter syntax.

## Steps to add a skill

Step 1: Draft the skill file following the template and the tone of the existing skills in this repo.
Step 2: Name the file in kebab-case, for example my-new-skill.md.
Step 3: Add the file to this repository.
Step 4: Add one worked trigger-example prompt for the new skill to SKILLS.md, matching the existing format.
Step 5: Update the skills list in README.md.
Step 6: Save it as an active Claude skill so it actually triggers in conversation.

## Quality bar

A good skill description names the specific tasks and phrasings that should trigger it, not just a topic area. A good skill body gives Claude a clear identity, a workflow for handling ambiguous requests, and a concrete output standard, the same shape as the 12 skills already in this repo.
