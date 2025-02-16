**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1781-845:62184] *** Process received signal ***
[fv-az1781-845:62184] Signal: Aborted (6)
[fv-az1781-845:62184] Signal code:  (-6)
[fv-az1781-845:62184] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5318845330]
[fv-az1781-845:62184] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f531889eb2c]
[fv-az1781-845:62184] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f531884527e]
[fv-az1781-845:62184] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f53188288ff]
[fv-az1781-845:62184] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5318ca5ff5]
[fv-az1781-845:62184] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5318cbb0da]
[fv-az1781-845:62184] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5318ca5a55]
[fv-az1781-845:62184] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5318ca5a6f]
[fv-az1781-845:62184] [ 8] plumed(+0x146dd)[0x5638047136dd]
[fv-az1781-845:62184] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f531882a1ca]
[fv-az1781-845:62184] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f531882a28b]
[fv-az1781-845:62184] [11] plumed(+0x15365)[0x563804714365]
[fv-az1781-845:62184] *** End of error message ***
</pre>
{% endraw %}
