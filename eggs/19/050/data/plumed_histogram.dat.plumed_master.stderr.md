**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmmtnos:36797] *** Process received signal ***
[runnervmmtnos:36797] Signal: Aborted (6)
[runnervmmtnos:36797] Signal code:  (-6)
[runnervmmtnos:36797] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb46f045330]
[runnervmmtnos:36797] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb46f09eb2c]
[runnervmmtnos:36797] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb46f04527e]
[runnervmmtnos:36797] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb46f0288ff]
[runnervmmtnos:36797] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb46f4a5ff5]
[runnervmmtnos:36797] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb46f4bb0da]
[runnervmmtnos:36797] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb46f4a5a55]
[runnervmmtnos:36797] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb46f4a5a6f]
[runnervmmtnos:36797] [ 8] plumed_master(+0x146dd)[0x559dca86c6dd]
[runnervmmtnos:36797] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb46f02a1ca]
[runnervmmtnos:36797] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb46f02a28b]
[runnervmmtnos:36797] [11] plumed_master(+0x15365)[0x559dca86d365]
[runnervmmtnos:36797] *** End of error message ***
</pre>
{% endraw %}
