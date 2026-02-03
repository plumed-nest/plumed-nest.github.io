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
[runnervmkj6or:08677] *** Process received signal ***
[runnervmkj6or:08677] Signal: Aborted (6)
[runnervmkj6or:08677] Signal code:  (-6)
[runnervmkj6or:08677] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6682645330]
[runnervmkj6or:08677] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f668269eb2c]
[runnervmkj6or:08677] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f668264527e]
[runnervmkj6or:08677] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f66826288ff]
[runnervmkj6or:08677] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6682aa5ff5]
[runnervmkj6or:08677] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6682abb0da]
[runnervmkj6or:08677] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6682aa5a55]
[runnervmkj6or:08677] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6682aa5a6f]
[runnervmkj6or:08677] [ 8] plumed(+0x146dd)[0x55f9dec0f6dd]
[runnervmkj6or:08677] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f668262a1ca]
[runnervmkj6or:08677] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f668262a28b]
[runnervmkj6or:08677] [11] plumed(+0x15365)[0x55f9dec10365]
[runnervmkj6or:08677] *** End of error message ***
</pre>
{% endraw %}
