**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmeorf1:06749] *** Process received signal ***
[runnervmeorf1:06749] Signal: Aborted (6)
[runnervmeorf1:06749] Signal code:  (-6)
[runnervmeorf1:06749] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f939ee45330]
[runnervmeorf1:06749] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f939ee9eb2c]
[runnervmeorf1:06749] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f939ee4527e]
[runnervmeorf1:06749] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f939ee288ff]
[runnervmeorf1:06749] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f939f2a5ff5]
[runnervmeorf1:06749] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f939f2bb0da]
[runnervmeorf1:06749] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f939f2a5a55]
[runnervmeorf1:06749] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f939f2a5a6f]
[runnervmeorf1:06749] [ 8] plumed(+0x146dd)[0x560d377ff6dd]
[runnervmeorf1:06749] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f939ee2a1ca]
[runnervmeorf1:06749] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f939ee2a28b]
[runnervmeorf1:06749] [11] plumed(+0x15365)[0x560d37800365]
[runnervmeorf1:06749] *** End of error message ***
</pre>
{% endraw %}
