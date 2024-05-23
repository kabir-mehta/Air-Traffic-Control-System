Used different OS concepts such as inter-process communication, multi-threading, synchronization, etc. to create an Air Traffic Control System.
This system consists of the following entities (simulated as processes):
  1. Plane (Each plane is a single-threaded process). Two types of planes are considered : Passanger plane & Cargo plane.
  2. Airport (Each airport is a multi-threaded process)
  3. Air Traffic Controller (This is a single-threaded process)
  4. Passenger traveling on a specific passenger plane (Each passenger process is a child of the corresponding plane process and each passenger process is single-threaded)
  5. Cleanup (This is a single-threaded process)
All programs are POSIX-compliant C programs.
