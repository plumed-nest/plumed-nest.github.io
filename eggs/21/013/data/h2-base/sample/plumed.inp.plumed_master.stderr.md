**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-base/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @18 : keyword ARG is compulsory for this action
[runnervmw9dnm:11076] *** Process received signal ***
[runnervmw9dnm:11076] Signal: Aborted (6)
[runnervmw9dnm:11076] Signal code:  (-6)
[runnervmw9dnm:11076] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe9d8845330]
[runnervmw9dnm:11076] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe9d889eb2c]
[runnervmw9dnm:11076] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe9d884527e]
[runnervmw9dnm:11076] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe9d88288ff]
[runnervmw9dnm:11076] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe9d8ca5ff5]
[runnervmw9dnm:11076] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe9d8cbb0da]
[runnervmw9dnm:11076] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe9d8ca5a55]
[runnervmw9dnm:11076] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe9d8ca5a6f]
[runnervmw9dnm:11076] [ 8] plumed_master(+0x146dd)[0x556de754a6dd]
[runnervmw9dnm:11076] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe9d882a1ca]
[runnervmw9dnm:11076] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe9d882a28b]
[runnervmw9dnm:11076] [11] plumed_master(+0x15365)[0x556de754b365]
[runnervmw9dnm:11076] *** End of error message ***
</pre>
{% endraw %}
