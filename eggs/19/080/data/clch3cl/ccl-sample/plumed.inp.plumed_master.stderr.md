**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ccl-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmw9dnm:10799] *** Process received signal ***
[runnervmw9dnm:10799] Signal: Aborted (6)
[runnervmw9dnm:10799] Signal code:  (-6)
[runnervmw9dnm:10799] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f18dbe45330]
[runnervmw9dnm:10799] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f18dbe9eb2c]
[runnervmw9dnm:10799] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f18dbe4527e]
[runnervmw9dnm:10799] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f18dbe288ff]
[runnervmw9dnm:10799] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f18dc2a5ff5]
[runnervmw9dnm:10799] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f18dc2bb0da]
[runnervmw9dnm:10799] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f18dc2a5a55]
[runnervmw9dnm:10799] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f18dc2a5a6f]
[runnervmw9dnm:10799] [ 8] plumed_master(+0x146dd)[0x5590cec336dd]
[runnervmw9dnm:10799] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f18dbe2a1ca]
[runnervmw9dnm:10799] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f18dbe2a28b]
[runnervmw9dnm:10799] [11] plumed_master(+0x15365)[0x5590cec34365]
[runnervmw9dnm:10799] *** End of error message ***
</pre>
{% endraw %}
