**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmq0rgcvqdmg:08643] *** Process received signal ***
[pkrvmq0rgcvqdmg:08643] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08643] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08643] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f033f045330]
[pkrvmq0rgcvqdmg:08643] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f033f09eb2c]
[pkrvmq0rgcvqdmg:08643] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f033f04527e]
[pkrvmq0rgcvqdmg:08643] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f033f0288ff]
[pkrvmq0rgcvqdmg:08643] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f033f4a5ff5]
[pkrvmq0rgcvqdmg:08643] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f033f4bb0da]
[pkrvmq0rgcvqdmg:08643] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f033f4a5a55]
[pkrvmq0rgcvqdmg:08643] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f033f4a5a6f]
[pkrvmq0rgcvqdmg:08643] [ 8] plumed(+0x146dd)[0x55575b1366dd]
[pkrvmq0rgcvqdmg:08643] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f033f02a1ca]
[pkrvmq0rgcvqdmg:08643] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f033f02a28b]
[pkrvmq0rgcvqdmg:08643] [11] plumed(+0x15365)[0x55575b137365]
[pkrvmq0rgcvqdmg:08643] *** End of error message ***
</pre>
{% endraw %}
