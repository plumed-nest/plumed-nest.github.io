**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[runnervmgx7h7:05641] *** Process received signal ***
[runnervmgx7h7:05641] Signal: Aborted (6)
[runnervmgx7h7:05641] Signal code:  (-6)
[runnervmgx7h7:05641] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f325ea45330]
[runnervmgx7h7:05641] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f325ea9ec0c]
[runnervmgx7h7:05641] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f325ea4527e]
[runnervmgx7h7:05641] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f325ea288ff]
[runnervmgx7h7:05641] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f325eea5ff5]
[runnervmgx7h7:05641] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f325eebb0da]
[runnervmgx7h7:05641] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f325eea5a55]
[runnervmgx7h7:05641] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f325eea5a6f]
[runnervmgx7h7:05641] [ 8] plumed_master(+0x146dd)[0x55f3f6b776dd]
[runnervmgx7h7:05641] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f325ea2a1ca]
[runnervmgx7h7:05641] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f325ea2a28b]
[runnervmgx7h7:05641] [11] plumed_master(+0x15365)[0x55f3f6b78365]
[runnervmgx7h7:05641] *** End of error message ***
</pre>
{% endraw %}
