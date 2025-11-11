**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ch-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @25 : keyword ARG is compulsory for this action
[runnervmw9dnm:10864] *** Process received signal ***
[runnervmw9dnm:10864] Signal: Aborted (6)
[runnervmw9dnm:10864] Signal code:  (-6)
[runnervmw9dnm:10864] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f906c845330]
[runnervmw9dnm:10864] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f906c89eb2c]
[runnervmw9dnm:10864] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f906c84527e]
[runnervmw9dnm:10864] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f906c8288ff]
[runnervmw9dnm:10864] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f906cca5ff5]
[runnervmw9dnm:10864] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f906ccbb0da]
[runnervmw9dnm:10864] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f906cca5a55]
[runnervmw9dnm:10864] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f906cca5a6f]
[runnervmw9dnm:10864] [ 8] plumed_master(+0x146dd)[0x56510c09a6dd]
[runnervmw9dnm:10864] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f906c82a1ca]
[runnervmw9dnm:10864] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f906c82a28b]
[runnervmw9dnm:10864] [11] plumed_master(+0x15365)[0x56510c09b365]
[runnervmw9dnm:10864] *** End of error message ***
</pre>
{% endraw %}
