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
[runnervmvrwv9:07653] *** Process received signal ***
[runnervmvrwv9:07653] Signal: Aborted (6)
[runnervmvrwv9:07653] Signal code:  (-6)
[runnervmvrwv9:07653] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4f73845330]
[runnervmvrwv9:07653] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4f7389eb2c]
[runnervmvrwv9:07653] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4f7384527e]
[runnervmvrwv9:07653] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4f738288ff]
[runnervmvrwv9:07653] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4f73ca5ff5]
[runnervmvrwv9:07653] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4f73cbb0da]
[runnervmvrwv9:07653] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4f73ca5a55]
[runnervmvrwv9:07653] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4f73ca5a6f]
[runnervmvrwv9:07653] [ 8] plumed(+0x146dd)[0x556fe2f0c6dd]
[runnervmvrwv9:07653] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4f7382a1ca]
[runnervmvrwv9:07653] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4f7382a28b]
[runnervmvrwv9:07653] [11] plumed(+0x15365)[0x556fe2f0d365]
[runnervmvrwv9:07653] *** End of error message ***
</pre>
{% endraw %}
