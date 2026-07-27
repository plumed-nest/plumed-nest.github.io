**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmvrwv9:07044] *** Process received signal ***
[runnervmvrwv9:07044] Signal: Aborted (6)
[runnervmvrwv9:07044] Signal code:  (-6)
[runnervmvrwv9:07044] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4b9c445330]
[runnervmvrwv9:07044] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4b9c49eb2c]
[runnervmvrwv9:07044] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4b9c44527e]
[runnervmvrwv9:07044] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4b9c4288ff]
[runnervmvrwv9:07044] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4b9c8a5ff5]
[runnervmvrwv9:07044] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4b9c8bb0da]
[runnervmvrwv9:07044] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4b9c8a5a55]
[runnervmvrwv9:07044] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4b9c8a5a6f]
[runnervmvrwv9:07044] [ 8] plumed(+0x146dd)[0x561633c226dd]
[runnervmvrwv9:07044] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4b9c42a1ca]
[runnervmvrwv9:07044] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4b9c42a28b]
[runnervmvrwv9:07044] [11] plumed(+0x15365)[0x561633c23365]
[runnervmvrwv9:07044] *** End of error message ***
</pre>
{% endraw %}
