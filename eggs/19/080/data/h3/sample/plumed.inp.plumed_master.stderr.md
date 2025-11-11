**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmw9dnm:11041] *** Process received signal ***
[runnervmw9dnm:11041] Signal: Aborted (6)
[runnervmw9dnm:11041] Signal code:  (-6)
[runnervmw9dnm:11041] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8403a45330]
[runnervmw9dnm:11041] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8403a9eb2c]
[runnervmw9dnm:11041] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8403a4527e]
[runnervmw9dnm:11041] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8403a288ff]
[runnervmw9dnm:11041] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8403ea5ff5]
[runnervmw9dnm:11041] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8403ebb0da]
[runnervmw9dnm:11041] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8403ea5a55]
[runnervmw9dnm:11041] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8403ea5a6f]
[runnervmw9dnm:11041] [ 8] plumed_master(+0x146dd)[0x557daa0ee6dd]
[runnervmw9dnm:11041] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8403a2a1ca]
[runnervmw9dnm:11041] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8403a2a28b]
[runnervmw9dnm:11041] [11] plumed_master(+0x15365)[0x557daa0ef365]
[runnervmw9dnm:11041] *** End of error message ***
</pre>
{% endraw %}
