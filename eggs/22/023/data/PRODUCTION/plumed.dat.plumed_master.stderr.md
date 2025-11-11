**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[runnervmw9dnm:09072] *** Process received signal ***
[runnervmw9dnm:09072] Signal: Aborted (6)
[runnervmw9dnm:09072] Signal code:  (-6)
[runnervmw9dnm:09072] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7b16845330]
[runnervmw9dnm:09072] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7b1689eb2c]
[runnervmw9dnm:09072] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7b1684527e]
[runnervmw9dnm:09072] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7b168288ff]
[runnervmw9dnm:09072] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7b16ca5ff5]
[runnervmw9dnm:09072] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7b16cbb0da]
[runnervmw9dnm:09072] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7b16ca5a55]
[runnervmw9dnm:09072] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7b16ca5a6f]
[runnervmw9dnm:09072] [ 8] plumed_master(+0x146dd)[0x55bef0ae56dd]
[runnervmw9dnm:09072] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7b1682a1ca]
[runnervmw9dnm:09072] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7b1682a28b]
[runnervmw9dnm:09072] [11] plumed_master(+0x15365)[0x55bef0ae6365]
[runnervmw9dnm:09072] *** End of error message ***
</pre>
{% endraw %}
