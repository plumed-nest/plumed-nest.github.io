**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[runnervm76f27:07623] *** Process received signal ***
[runnervm76f27:07623] Signal: Aborted (6)
[runnervm76f27:07623] Signal code:  (-6)
[runnervm76f27:07623] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f235fe45330]
[runnervm76f27:07623] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f235fe9ec0c]
[runnervm76f27:07623] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f235fe4527e]
[runnervm76f27:07623] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f235fe288ff]
[runnervm76f27:07623] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23602a5ff5]
[runnervm76f27:07623] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23602bb0da]
[runnervm76f27:07623] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23602a5a55]
[runnervm76f27:07623] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23602a5a6f]
[runnervm76f27:07623] [ 8] plumed(+0x146dd)[0x564e0dd0a6dd]
[runnervm76f27:07623] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f235fe2a1ca]
[runnervm76f27:07623] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f235fe2a28b]
[runnervm76f27:07623] [11] plumed(+0x15365)[0x564e0dd0b365]
[runnervm76f27:07623] *** End of error message ***
</pre>
{% endraw %}
