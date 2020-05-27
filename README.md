# Message-Passing

TCP connections within an OTP supervision tree.

To run it:1> First compile the erlang file (example_tcp).
          2> run : example_tcp:start_server(8091).

Now open the second terminal and open a telnet client : $ telnet localhost 8091

To close the shell simply type : quit
