**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmvrwv9:07101] *** Process received signal ***
[runnervmvrwv9:07101] Signal: Aborted (6)
[runnervmvrwv9:07101] Signal code:  (-6)
[runnervmvrwv9:07101] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f378f645330]
[runnervmvrwv9:07101] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f378f69eb2c]
[runnervmvrwv9:07101] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f378f64527e]
[runnervmvrwv9:07101] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f378f6288ff]
[runnervmvrwv9:07101] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f378faa5ff5]
[runnervmvrwv9:07101] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f378fabb0da]
[runnervmvrwv9:07101] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f378faa5a55]
[runnervmvrwv9:07101] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f378faa5a6f]
[runnervmvrwv9:07101] [ 8] plumed(+0x146dd)[0x55eac3df36dd]
[runnervmvrwv9:07101] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f378f62a1ca]
[runnervmvrwv9:07101] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f378f62a28b]
[runnervmvrwv9:07101] [11] plumed(+0x15365)[0x55eac3df4365]
[runnervmvrwv9:07101] *** End of error message ***
</pre>
{% endraw %}
