**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmmklqx:10469] *** Process received signal ***
[runnervmmklqx:10469] Signal: Aborted (6)
[runnervmmklqx:10469] Signal code:  (-6)
[runnervmmklqx:10469] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9a44445330]
[runnervmmklqx:10469] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9a4449eb2c]
[runnervmmklqx:10469] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9a4444527e]
[runnervmmklqx:10469] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9a444288ff]
[runnervmmklqx:10469] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9a448a5ff5]
[runnervmmklqx:10469] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9a448bb0da]
[runnervmmklqx:10469] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9a448a5a55]
[runnervmmklqx:10469] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9a448a5a6f]
[runnervmmklqx:10469] [ 8] plumed_master(+0x146dd)[0x562f846d46dd]
[runnervmmklqx:10469] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9a4442a1ca]
[runnervmmklqx:10469] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9a4442a28b]
[runnervmmklqx:10469] [11] plumed_master(+0x15365)[0x562f846d5365]
[runnervmmklqx:10469] *** End of error message ***
</pre>
{% endraw %}
