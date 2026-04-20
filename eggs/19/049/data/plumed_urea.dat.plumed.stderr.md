**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[runnervmeorf1:11214] *** Process received signal ***
[runnervmeorf1:11214] Signal: Aborted (6)
[runnervmeorf1:11214] Signal code:  (-6)
[runnervmeorf1:11214] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f741ec45330]
[runnervmeorf1:11214] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f741ec9eb2c]
[runnervmeorf1:11214] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f741ec4527e]
[runnervmeorf1:11214] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f741ec288ff]
[runnervmeorf1:11214] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f741f0a5ff5]
[runnervmeorf1:11214] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f741f0bb0da]
[runnervmeorf1:11214] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f741f0a5a55]
[runnervmeorf1:11214] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f741f0a5a6f]
[runnervmeorf1:11214] [ 8] plumed(+0x146dd)[0x55e26408d6dd]
[runnervmeorf1:11214] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f741ec2a1ca]
[runnervmeorf1:11214] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f741ec2a28b]
[runnervmeorf1:11214] [11] plumed(+0x15365)[0x55e26408e365]
[runnervmeorf1:11214] *** End of error message ***
</pre>
{% endraw %}
