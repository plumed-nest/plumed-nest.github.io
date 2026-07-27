**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[runnervmvrwv9:10207] *** Process received signal ***
[runnervmvrwv9:10207] Signal: Aborted (6)
[runnervmvrwv9:10207] Signal code:  (-6)
[runnervmvrwv9:10207] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8808245330]
[runnervmvrwv9:10207] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f880829eb2c]
[runnervmvrwv9:10207] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f880824527e]
[runnervmvrwv9:10207] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f88082288ff]
[runnervmvrwv9:10207] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f88086a5ff5]
[runnervmvrwv9:10207] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f88086bb0da]
[runnervmvrwv9:10207] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f88086a5a55]
[runnervmvrwv9:10207] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f88086a5a6f]
[runnervmvrwv9:10207] [ 8] plumed(+0x146dd)[0x55db63c346dd]
[runnervmvrwv9:10207] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f880822a1ca]
[runnervmvrwv9:10207] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f880822a28b]
[runnervmvrwv9:10207] [11] plumed(+0x15365)[0x55db63c35365]
[runnervmvrwv9:10207] *** End of error message ***
</pre>
{% endraw %}
