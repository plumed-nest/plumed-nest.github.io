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
[runnervmw9dnm:11174] *** Process received signal ***
[runnervmw9dnm:11174] Signal: Aborted (6)
[runnervmw9dnm:11174] Signal code:  (-6)
[runnervmw9dnm:11174] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f06f1245330]
[runnervmw9dnm:11174] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f06f129eb2c]
[runnervmw9dnm:11174] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f06f124527e]
[runnervmw9dnm:11174] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f06f12288ff]
[runnervmw9dnm:11174] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f06f16a5ff5]
[runnervmw9dnm:11174] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f06f16bb0da]
[runnervmw9dnm:11174] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f06f16a5a55]
[runnervmw9dnm:11174] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f06f16a5a6f]
[runnervmw9dnm:11174] [ 8] plumed_master(+0x146dd)[0x558d9d6db6dd]
[runnervmw9dnm:11174] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f06f122a1ca]
[runnervmw9dnm:11174] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f06f122a28b]
[runnervmw9dnm:11174] [11] plumed_master(+0x15365)[0x558d9d6dc365]
[runnervmw9dnm:11174] *** End of error message ***
</pre>
{% endraw %}
