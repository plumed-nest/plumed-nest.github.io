**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmvrwv9:07152] *** Process received signal ***
[runnervmvrwv9:07152] Signal: Aborted (6)
[runnervmvrwv9:07152] Signal code:  (-6)
[runnervmvrwv9:07152] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f355f645330]
[runnervmvrwv9:07152] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f355f69eb2c]
[runnervmvrwv9:07152] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f355f64527e]
[runnervmvrwv9:07152] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f355f6288ff]
[runnervmvrwv9:07152] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f355faa5ff5]
[runnervmvrwv9:07152] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f355fabb0da]
[runnervmvrwv9:07152] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f355faa5a55]
[runnervmvrwv9:07152] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f355faa5a6f]
[runnervmvrwv9:07152] [ 8] plumed(+0x146dd)[0x558ab39d16dd]
[runnervmvrwv9:07152] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f355f62a1ca]
[runnervmvrwv9:07152] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f355f62a28b]
[runnervmvrwv9:07152] [11] plumed(+0x15365)[0x558ab39d2365]
[runnervmvrwv9:07152] *** End of error message ***
</pre>
{% endraw %}
