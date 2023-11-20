<p align="center">
  <a href="https://github.com/hi764/le_priority/releases/tag/1.0.3" title="Release"><img alt="Release" src="https://img.shields.io/github/v/release/hi764/le_priority"></a>
  <a href="LICENSE" title="License"><img alt="License" src="https://img.shields.io/github/license/hi764/le_priority.svg"></a>
</p>

<h4 align="center">
  FiveM Priority Resource by Luke.
</h4>

## Commands

- `/inprogress` - Starts priority (available to everyone).
- `/cooldown` - Initiates cooldown; the person starting the priority can trigger this (default cooldown is 15 minutes).

## Staff Commands

(Requires the appropriate ace permission, configurable in the resource's configuration file)

- `/resetpcd` - Resets the cooldown and sets the priority to 'Inactive'.
- `/cooldown [mins]` - Staff can start cooldowns with a custom timer.

## Permissions
**These permissions go in the bottom of your server.cfg | WARNING: If you do not know what you're doing, search it up!**
`add_ace group.admin le_priority.command.resetpcd allow
add_ace group.admin le_priority.command.inprogress allow
add_ace group.admin le_priority.command.cooldown allow`

**Note:**

- Staff members can always initiate a cooldown.
- Cooldown will commence if the person who started a priority disconnects from the server.
