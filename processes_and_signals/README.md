# Processes and Signals

This directory contains Bash scripts that demonstrate Linux process management and signal handling.

## Scripts

- **0-what-is-my-pid**: Displays the PID of the current script
- **1-list_your_processes**: Lists all running processes for all users with hierarchy
- **2-show_your_bash_pid**: Displays lines containing bash from the process list
- **3-show_your_bash_pid_made_easy**: Displays PID and name of bash processes using pgrep
- **4-to_infinity_and_beyond**: Displays "To infinity and beyond" indefinitely
- **5-dont_stop_me_now**: Stops the 4-to_infinity_and_beyond process using kill
- **6-stop_me_if_you_can**: Stops the 4-to_infinity_and_beyond process without kill or killall
- **7-highlander**: Loops forever and responds to SIGTERM with "I am invincible!!!"
- **67-stop_me_if_you_can**: Stops the 7-highlander process
- **8-beheaded_process**: Kills the 7-highlander process with SIGKILL
- **10-process_and_pid_file**: Creates a PID file and handles multiple signals
- **manage_my_process**: Daemon that writes "I am alive!" to /tmp/my_process
- **11-manage_my_process**: Init script to start, stop, and restart manage_my_process
