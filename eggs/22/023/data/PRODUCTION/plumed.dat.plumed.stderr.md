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
[fv-az816-356:08470] *** Process received signal ***
[fv-az816-356:08470] Signal: Aborted (6)
[fv-az816-356:08470] Signal code:  (-6)
[fv-az816-356:08470] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe0d7c45330]
[fv-az816-356:08470] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe0d7c9eb2c]
[fv-az816-356:08470] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe0d7c4527e]
[fv-az816-356:08470] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe0d7c288ff]
[fv-az816-356:08470] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe0d80a5ff5]
[fv-az816-356:08470] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe0d80bb0da]
[fv-az816-356:08470] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe0d80a5a55]
[fv-az816-356:08470] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe0d80a5a6f]
[fv-az816-356:08470] [ 8] plumed(+0x146dd)[0x55f7ff6c26dd]
[fv-az816-356:08470] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe0d7c2a1ca]
[fv-az816-356:08470] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe0d7c2a28b]
[fv-az816-356:08470] [11] plumed(+0x15365)[0x55f7ff6c3365]
[fv-az816-356:08470] *** End of error message ***
</pre>
{% endraw %}
