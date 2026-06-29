**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[runnervmmklqx:08364] *** Process received signal ***
[runnervmmklqx:08364] Signal: Aborted (6)
[runnervmmklqx:08364] Signal code:  (-6)
[runnervmmklqx:08364] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2f75845330]
[runnervmmklqx:08364] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2f7589eb2c]
[runnervmmklqx:08364] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2f7584527e]
[runnervmmklqx:08364] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2f758288ff]
[runnervmmklqx:08364] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2f75ca5ff5]
[runnervmmklqx:08364] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2f75cbb0da]
[runnervmmklqx:08364] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2f75ca5a55]
[runnervmmklqx:08364] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2f75ca5a6f]
[runnervmmklqx:08364] [ 8] plumed(+0x146dd)[0x5562fb7c96dd]
[runnervmmklqx:08364] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2f7582a1ca]
[runnervmmklqx:08364] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2f7582a28b]
[runnervmmklqx:08364] [11] plumed(+0x15365)[0x5562fb7ca365]
[runnervmmklqx:08364] *** End of error message ***
</pre>
{% endraw %}
