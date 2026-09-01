**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmgx7h7:09495] *** Process received signal ***
[runnervmgx7h7:09495] Signal: Aborted (6)
[runnervmgx7h7:09495] Signal code:  (-6)
[runnervmgx7h7:09495] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe08c445330]
[runnervmgx7h7:09495] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe08c49ec0c]
[runnervmgx7h7:09495] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe08c44527e]
[runnervmgx7h7:09495] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe08c4288ff]
[runnervmgx7h7:09495] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe08c8a5ff5]
[runnervmgx7h7:09495] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe08c8bb0da]
[runnervmgx7h7:09495] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe08c8a5a55]
[runnervmgx7h7:09495] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe08c8a5a6f]
[runnervmgx7h7:09495] [ 8] plumed_master(+0x146dd)[0x563bf96686dd]
[runnervmgx7h7:09495] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe08c42a1ca]
[runnervmgx7h7:09495] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe08c42a28b]
[runnervmgx7h7:09495] [11] plumed_master(+0x15365)[0x563bf9669365]
[runnervmgx7h7:09495] *** End of error message ***
</pre>
{% endraw %}
