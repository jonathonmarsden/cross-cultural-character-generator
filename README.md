# Cross-Cultural Character Generator

A web-based tool for generating diverse character prompts for Midjourney, specifically designed for creating cross-cultural training materials to help people better understand each other across cultural boundaries.

## Features

- **Research-Based Expressions**: Based on Ekman's universal emotions and cross-cultural studies
- **Comprehensive Diversity Options**: Age, gender, ethnicity, profession, and additional attributes
- **Persistent Storage**: Save and manage characters between sessions
- **Export/Import**: Share character sets with team members
- **Search & Filter**: Quickly find saved characters
- **Consistent Style**: All prompts use the same seed for visual consistency

## Usage

1. **Create a Character**:
   - Enter a character name
   - Select attributes from each category
   - The Midjourney prompt updates automatically
   - Click "Save Character" to store for later use

2. **Manage Saved Characters**:
   - View all saved characters in the right panel
   - Search by name, profession, or other attributes
   - Load characters back into the editor
   - Delete unwanted characters

3. **Export/Import**:
   - Export all characters as JSON for backup or sharing
   - Import character sets from team members

## Prompt Structure

All generated prompts follow this structure:

- Consistent art style (flat vector illustration)
- Demographic details
- Professional attire
- Expression and body language
- Facing direction for conversation scenes
- Fixed seed (1580775571) for consistency

## Creating Conversation Scenes

To create characters that appear to be conversing:

1. Generate Character A facing right →
2. Generate Character B facing left ←
3. Place them on opposite sides of your slide

## Local Storage

Characters are saved in browser localStorage. Clear browser data will remove saved characters - use Export regularly for backups.
