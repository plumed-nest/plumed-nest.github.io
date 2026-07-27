**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmvrwv9:07373] *** Process received signal ***
[runnervmvrwv9:07373] Signal: Aborted (6)
[runnervmvrwv9:07373] Signal code:  (-6)
[runnervmvrwv9:07373] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f314ea45330]
[runnervmvrwv9:07373] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f314ea9eb2c]
[runnervmvrwv9:07373] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f314ea4527e]
[runnervmvrwv9:07373] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f314ea288ff]
[runnervmvrwv9:07373] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f314eea5ff5]
[runnervmvrwv9:07373] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f314eebb0da]
[runnervmvrwv9:07373] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f314eea5a55]
[runnervmvrwv9:07373] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f314eea5a6f]
[runnervmvrwv9:07373] [ 8] plumed_master(+0x146dd)[0x55729afcf6dd]
[runnervmvrwv9:07373] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f314ea2a1ca]
[runnervmvrwv9:07373] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f314ea2a28b]
[runnervmvrwv9:07373] [11] plumed_master(+0x15365)[0x55729afd0365]
[runnervmvrwv9:07373] *** End of error message ***
</pre>
{% endraw %}
