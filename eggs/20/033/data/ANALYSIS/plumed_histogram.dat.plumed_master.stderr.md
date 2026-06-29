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
[runnervmmklqx:09431] *** Process received signal ***
[runnervmmklqx:09431] Signal: Aborted (6)
[runnervmmklqx:09431] Signal code:  (-6)
[runnervmmklqx:09431] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2a9a445330]
[runnervmmklqx:09431] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2a9a49eb2c]
[runnervmmklqx:09431] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2a9a44527e]
[runnervmmklqx:09431] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2a9a4288ff]
[runnervmmklqx:09431] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2a9a8a5ff5]
[runnervmmklqx:09431] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2a9a8bb0da]
[runnervmmklqx:09431] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2a9a8a5a55]
[runnervmmklqx:09431] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2a9a8a5a6f]
[runnervmmklqx:09431] [ 8] plumed_master(+0x146dd)[0x55adf85076dd]
[runnervmmklqx:09431] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2a9a42a1ca]
[runnervmmklqx:09431] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2a9a42a28b]
[runnervmmklqx:09431] [11] plumed_master(+0x15365)[0x55adf8508365]
[runnervmmklqx:09431] *** End of error message ***
</pre>
{% endraw %}
