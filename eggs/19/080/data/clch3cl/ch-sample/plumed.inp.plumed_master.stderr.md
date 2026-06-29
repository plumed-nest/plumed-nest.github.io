**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ch-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @25 : keyword ARG is compulsory for this action
[runnervmmklqx:10289] *** Process received signal ***
[runnervmmklqx:10289] Signal: Aborted (6)
[runnervmmklqx:10289] Signal code:  (-6)
[runnervmmklqx:10289] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f155ee45330]
[runnervmmklqx:10289] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f155ee9eb2c]
[runnervmmklqx:10289] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f155ee4527e]
[runnervmmklqx:10289] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f155ee288ff]
[runnervmmklqx:10289] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f155f2a5ff5]
[runnervmmklqx:10289] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f155f2bb0da]
[runnervmmklqx:10289] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f155f2a5a55]
[runnervmmklqx:10289] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f155f2a5a6f]
[runnervmmklqx:10289] [ 8] plumed_master(+0x146dd)[0x558bc22ca6dd]
[runnervmmklqx:10289] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f155ee2a1ca]
[runnervmmklqx:10289] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f155ee2a28b]
[runnervmmklqx:10289] [11] plumed_master(+0x15365)[0x558bc22cb365]
[runnervmmklqx:10289] *** End of error message ***
</pre>
{% endraw %}
