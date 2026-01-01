### **Warning: this mod is not intended for public use. Minecraft *might* crash if you run this mod.**

## Downloads

**Latest version (1.19.2)**: [Latest](https://github.com/SnipeCope/welcome-message-modrinth/blob/main/releases/release%201.2.4/description.md)
**Latest version (1.18.2)**: [Latest](https://github.com/SnipeCope/welcome-message-modrinth/blob/main/releases/release%201.4.5/description.md)

**Past versions**: [Older versions](https://github.com/SnipeCope/welcome-message-modrinth/tree/main/releases)


# Data Usage & Storage Notice
## Overview

This mod performs limited client-side data storage solely for the purpose of **controlling the display behavior** of its welcome message functionality.

**NO** data is collected, transmitted, or shared beyond the local client environment.

## Stored Data

The mod stores the following information locally:

A boolean flag indicating whether the welcome message feature is enabled or disabled

A per-world (which does not work) or per-server identifier indicating whether the welcome message has already been shown

This data exists only to ensure that the welcome message is displayed exactly once per world or server, unless explicitly re-enabled by the user.

## Implementation Location

All data storage and retrieval logic is implemented within:

<code>src/main/java/com/snipecope/welcomemessagemod/WelcomeMessageMod.java</code>


The implementation uses Java’s standard java.util.prefs.Preferences API.

## Data Scope and Access

All stored data is saved locally on the client machine

No data is transmitted to servers or third parties

No network communication is performed in relation to this data

No other players or server operators can access this data

## Data Exclusions

This mod does not store, process, or collect:

- Personally identifiable information

- Account or authentication data

- IP addresses or network identifiers

- Gameplay metrics or behavioral analytics

- Server-side or shared data

## Purpose Limitation


All stored data is strictly limited to enabling the intended functionality of the mod and is not used for tracking, profiling, or analytics purposes.




