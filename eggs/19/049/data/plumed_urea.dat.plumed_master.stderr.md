**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s43 : missing SWITCH11 keyword
[runnervmkj6or:08693] *** Process received signal ***
[runnervmkj6or:08693] Signal: Aborted (6)
[runnervmkj6or:08693] Signal code:  (-6)
[runnervmkj6or:08693] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe013645330]
[runnervmkj6or:08693] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe01369eb2c]
[runnervmkj6or:08693] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe01364527e]
[runnervmkj6or:08693] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe0136288ff]
[runnervmkj6or:08693] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe013aa5ff5]
[runnervmkj6or:08693] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe013abb0da]
[runnervmkj6or:08693] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe013aa5a55]
[runnervmkj6or:08693] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe013aa5a6f]
[runnervmkj6or:08693] [ 8] plumed_master(+0x146dd)[0x5607525566dd]
[runnervmkj6or:08693] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe01362a1ca]
[runnervmkj6or:08693] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe01362a28b]
[runnervmkj6or:08693] [11] plumed_master(+0x15365)[0x560752557365]
[runnervmkj6or:08693] *** End of error message ***
</pre>
{% endraw %}
