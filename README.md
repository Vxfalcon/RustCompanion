<div align="center">
  <img src="icon.png" width="86" alt="Rust Companion icon">
  <h1>Rust Companion</h1>
  <p>Live maps, team tracking and a floating minimap for Rust.</p>
  <p><strong>Windows x64</strong> · <strong>Version 0.1.0</strong> · Rust+ pairing</p>
  <p><a href="#downloads"><strong>Download for Windows</strong></a></p>
</div>

## Downloads

| Build | How to use it |
| :--- | :--- |
| [Windows installer](https://github.com/Vxfalcon/RustCompanion/raw/refs/heads/main/downloads/RustCompanionSetup.exe) | Install Rust Companion and add a Start menu shortcut. |
| [Portable app](https://github.com/Vxfalcon/RustCompanion/raw/refs/heads/main/downloads/RustCompanionPortable.exe) | Open the app directly without an installer. |

## What’s inside

<table>
  <tr>
    <td width="52%">
      <h3>Map and minimap</h3>
      <p>See your team, center the map on yourself, and customize your player marker. The floating minimap follows your position and has transparent corners. Choose a rounded square or a circle, set its size, and toggle the Rust grid, monument names and decay pins in Settings.</p>
      <h3>Resource heatmaps</h3>
      <p>Find likely spawn areas for ores, animals, hemp and food using terrain from the map Rust caches on your PC.</p>
      <h3>Nemesis tracker</h3>
      <p>Count deaths from the Rust client log, set a nemesis threshold, and manage tracked players with expandable Steam profiles. Get alerts when their public Steam presence changes.</p>
      <h3>Team and base tools</h3>
      <p>Manage paired smart devices, use team chat commands, and check raid costs, recycling yields and decay timers.</p>
    </td>
    <td align="center"><img src="minimap.png" width="380" alt="Rust Companion minimap showing a player marker and high quality metal heatmap"></td>
  </tr>
</table>

## First run

1. Open **Settings** in Rust Companion and link your Steam account.
2. In Rust, join a server with Rust+ enabled and select **Pair with Server**.
3. Open **Map**, then select **Open minimap** under **Map Controls**.
4. Right-click the minimap to pick a resource heatmap. Scroll to zoom.
5. Press **Insert** to show or hide the main window.

The player arrow uses your direction of travel if the server omits facing data. Heatmap colors show estimated spawn density.

Test sounds play the original clips from your Steam installation of Rust. The app imports them locally the first time you play a test.

The Tracker needs Rust to write its client log. If the tab shows no log activity, add <code>-logfile output_log.txt</code> to the Steam launch options for Rust and restart the game. Presence alerts depend on public Steam status.

*An independent Windows app for Rust. Rust and Rust+ are products of Facepunch Studios.*

