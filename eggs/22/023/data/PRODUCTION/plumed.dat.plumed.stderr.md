**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[runnervmkj6or:06794] *** Process received signal ***
[runnervmkj6or:06794] Signal: Aborted (6)
[runnervmkj6or:06794] Signal code:  (-6)
[runnervmkj6or:06794] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f87d9a45330]
[runnervmkj6or:06794] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f87d9a9eb2c]
[runnervmkj6or:06794] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f87d9a4527e]
[runnervmkj6or:06794] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f87d9a288ff]
[runnervmkj6or:06794] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f87d9ea5ff5]
[runnervmkj6or:06794] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f87d9ebb0da]
[runnervmkj6or:06794] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f87d9ea5a55]
[runnervmkj6or:06794] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f87d9ea5a6f]
[runnervmkj6or:06794] [ 8] plumed(+0x146dd)[0x561fab9476dd]
[runnervmkj6or:06794] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f87d9a2a1ca]
[runnervmkj6or:06794] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f87d9a2a28b]
[runnervmkj6or:06794] [11] plumed(+0x15365)[0x561fab948365]
[runnervmkj6or:06794] *** End of error message ***
</pre>
{% endraw %}
