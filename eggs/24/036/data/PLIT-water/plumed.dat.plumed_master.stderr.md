**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervmw9dnm:06992] *** Process received signal ***
[runnervmw9dnm:06992] Signal: Aborted (6)
[runnervmw9dnm:06992] Signal code:  (-6)
[runnervmw9dnm:06992] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f25e9645330]
[runnervmw9dnm:06992] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f25e969eb2c]
[runnervmw9dnm:06992] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f25e964527e]
[runnervmw9dnm:06992] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f25e96288ff]
[runnervmw9dnm:06992] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f25e9aa5ff5]
[runnervmw9dnm:06992] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f25e9abb0da]
[runnervmw9dnm:06992] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f25e9aa5a55]
[runnervmw9dnm:06992] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f25e9aa5a6f]
[runnervmw9dnm:06992] [ 8] plumed_master(+0x146dd)[0x55de8deaa6dd]
[runnervmw9dnm:06992] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f25e962a1ca]
[runnervmw9dnm:06992] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f25e962a28b]
[runnervmw9dnm:06992] [11] plumed_master(+0x15365)[0x55de8deab365]
[runnervmw9dnm:06992] *** End of error message ***
</pre>
{% endraw %}
