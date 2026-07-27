**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s43 : missing SWITCH11 keyword
[runnervmvrwv9:10223] *** Process received signal ***
[runnervmvrwv9:10223] Signal: Aborted (6)
[runnervmvrwv9:10223] Signal code:  (-6)
[runnervmvrwv9:10223] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f361da45330]
[runnervmvrwv9:10223] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f361da9eb2c]
[runnervmvrwv9:10223] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f361da4527e]
[runnervmvrwv9:10223] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f361da288ff]
[runnervmvrwv9:10223] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f361dea5ff5]
[runnervmvrwv9:10223] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f361debb0da]
[runnervmvrwv9:10223] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f361dea5a55]
[runnervmvrwv9:10223] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f361dea5a6f]
[runnervmvrwv9:10223] [ 8] plumed_master(+0x146dd)[0x55b8cfff26dd]
[runnervmvrwv9:10223] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f361da2a1ca]
[runnervmvrwv9:10223] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f361da2a28b]
[runnervmvrwv9:10223] [11] plumed_master(+0x15365)[0x55b8cfff3365]
[runnervmvrwv9:10223] *** End of error message ***
</pre>
{% endraw %}
