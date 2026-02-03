**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[runnervmkj6or:06509] *** Process received signal ***
[runnervmkj6or:06509] Signal: Aborted (6)
[runnervmkj6or:06509] Signal code:  (-6)
[runnervmkj6or:06509] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe516645330]
[runnervmkj6or:06509] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe51669eb2c]
[runnervmkj6or:06509] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe51664527e]
[runnervmkj6or:06509] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5166288ff]
[runnervmkj6or:06509] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe516aa5ff5]
[runnervmkj6or:06509] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe516abb0da]
[runnervmkj6or:06509] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe516aa5a55]
[runnervmkj6or:06509] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe516aa5a6f]
[runnervmkj6or:06509] [ 8] plumed(+0x146dd)[0x556881c2a6dd]
[runnervmkj6or:06509] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe51662a1ca]
[runnervmkj6or:06509] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe51662a28b]
[runnervmkj6or:06509] [11] plumed(+0x15365)[0x556881c2b365]
[runnervmkj6or:06509] *** End of error message ***
</pre>
{% endraw %}
