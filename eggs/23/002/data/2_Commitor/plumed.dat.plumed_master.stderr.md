**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmvrwv9:07270] *** Process received signal ***
[runnervmvrwv9:07270] Signal: Aborted (6)
[runnervmvrwv9:07270] Signal code:  (-6)
[runnervmvrwv9:07270] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2359245330]
[runnervmvrwv9:07270] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f235929eb2c]
[runnervmvrwv9:07270] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f235924527e]
[runnervmvrwv9:07270] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23592288ff]
[runnervmvrwv9:07270] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23596a5ff5]
[runnervmvrwv9:07270] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23596bb0da]
[runnervmvrwv9:07270] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23596a5a55]
[runnervmvrwv9:07270] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23596a5a6f]
[runnervmvrwv9:07270] [ 8] plumed_master(+0x146dd)[0x55affe2d06dd]
[runnervmvrwv9:07270] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f235922a1ca]
[runnervmvrwv9:07270] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f235922a28b]
[runnervmvrwv9:07270] [11] plumed_master(+0x15365)[0x55affe2d1365]
[runnervmvrwv9:07270] *** End of error message ***
</pre>
{% endraw %}
