**Project ID:** [plumID:21.001]({{ '/' | absolute_url }}eggs/21/001/)  
Stderr for source:  HS6ST/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @37 : keyword ARG is compulsory for this action
[runnervmmtnos:36014] *** Process received signal ***
[runnervmmtnos:36014] Signal: Aborted (6)
[runnervmmtnos:36014] Signal code:  (-6)
[runnervmmtnos:36014] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8466c45330]
[runnervmmtnos:36014] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8466c9eb2c]
[runnervmmtnos:36014] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8466c4527e]
[runnervmmtnos:36014] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8466c288ff]
[runnervmmtnos:36014] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f84670a5ff5]
[runnervmmtnos:36014] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f84670bb0da]
[runnervmmtnos:36014] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f84670a5a55]
[runnervmmtnos:36014] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f84670a5a6f]
[runnervmmtnos:36014] [ 8] plumed_master(+0x146dd)[0x5642c73986dd]
[runnervmmtnos:36014] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8466c2a1ca]
[runnervmmtnos:36014] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8466c2a28b]
[runnervmmtnos:36014] [11] plumed_master(+0x15365)[0x5642c7399365]
[runnervmmtnos:36014] *** End of error message ***
</pre>
{% endraw %}
