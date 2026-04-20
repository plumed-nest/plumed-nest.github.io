**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmeorf1:06800] *** Process received signal ***
[runnervmeorf1:06800] Signal: Aborted (6)
[runnervmeorf1:06800] Signal code:  (-6)
[runnervmeorf1:06800] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff15dc45330]
[runnervmeorf1:06800] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff15dc9eb2c]
[runnervmeorf1:06800] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff15dc4527e]
[runnervmeorf1:06800] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff15dc288ff]
[runnervmeorf1:06800] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff15e0a5ff5]
[runnervmeorf1:06800] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff15e0bb0da]
[runnervmeorf1:06800] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff15e0a5a55]
[runnervmeorf1:06800] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff15e0a5a6f]
[runnervmeorf1:06800] [ 8] plumed(+0x146dd)[0x5592e9a756dd]
[runnervmeorf1:06800] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff15dc2a1ca]
[runnervmeorf1:06800] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff15dc2a28b]
[runnervmeorf1:06800] [11] plumed(+0x15365)[0x5592e9a76365]
[runnervmeorf1:06800] *** End of error message ***
</pre>
{% endraw %}
