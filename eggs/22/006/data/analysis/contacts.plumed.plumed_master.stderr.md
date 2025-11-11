**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @69 : keyword ARG is compulsory for this action
[runnervmw9dnm:09227] *** Process received signal ***
[runnervmw9dnm:09227] Signal: Aborted (6)
[runnervmw9dnm:09227] Signal code:  (-6)
[runnervmw9dnm:09227] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa638645330]
[runnervmw9dnm:09227] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa63869eb2c]
[runnervmw9dnm:09227] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa63864527e]
[runnervmw9dnm:09227] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa6386288ff]
[runnervmw9dnm:09227] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa638aa5ff5]
[runnervmw9dnm:09227] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa638abb0da]
[runnervmw9dnm:09227] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa638aa5a55]
[runnervmw9dnm:09227] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa638aa5a6f]
[runnervmw9dnm:09227] [ 8] plumed_master(+0x146dd)[0x55f7f567f6dd]
[runnervmw9dnm:09227] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa63862a1ca]
[runnervmw9dnm:09227] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa63862a28b]
[runnervmw9dnm:09227] [11] plumed_master(+0x15365)[0x55f7f5680365]
[runnervmw9dnm:09227] *** End of error message ***
</pre>
{% endraw %}
