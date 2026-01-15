**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  dimer/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[runnervmmtnos:34034] *** Process received signal ***
[runnervmmtnos:34034] Signal: Aborted (6)
[runnervmmtnos:34034] Signal code:  (-6)
[runnervmmtnos:34034] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f73e4245330]
[runnervmmtnos:34034] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f73e429eb2c]
[runnervmmtnos:34034] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f73e424527e]
[runnervmmtnos:34034] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f73e42288ff]
[runnervmmtnos:34034] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f73e46a5ff5]
[runnervmmtnos:34034] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f73e46bb0da]
[runnervmmtnos:34034] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f73e46a5a55]
[runnervmmtnos:34034] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f73e46a5a6f]
[runnervmmtnos:34034] [ 8] plumed_master(+0x146dd)[0x55d428b1d6dd]
[runnervmmtnos:34034] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f73e422a1ca]
[runnervmmtnos:34034] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f73e422a28b]
[runnervmmtnos:34034] [11] plumed_master(+0x15365)[0x55d428b1e365]
[runnervmmtnos:34034] *** End of error message ***
</pre>
{% endraw %}
