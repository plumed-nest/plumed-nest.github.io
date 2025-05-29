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
[pkrvmf6wy0o8zjz:65332] *** Process received signal ***
[pkrvmf6wy0o8zjz:65332] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:65332] Signal code:  (-6)
[pkrvmf6wy0o8zjz:65332] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd7f9645330]
[pkrvmf6wy0o8zjz:65332] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd7f969eb2c]
[pkrvmf6wy0o8zjz:65332] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd7f964527e]
[pkrvmf6wy0o8zjz:65332] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7f96288ff]
[pkrvmf6wy0o8zjz:65332] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd7f9aa5ff5]
[pkrvmf6wy0o8zjz:65332] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd7f9abb0da]
[pkrvmf6wy0o8zjz:65332] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd7f9aa5a55]
[pkrvmf6wy0o8zjz:65332] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd7f9aa5a6f]
[pkrvmf6wy0o8zjz:65332] [ 8] plumed(+0x146dd)[0x55da9d22a6dd]
[pkrvmf6wy0o8zjz:65332] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd7f962a1ca]
[pkrvmf6wy0o8zjz:65332] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd7f962a28b]
[pkrvmf6wy0o8zjz:65332] [11] plumed(+0x15365)[0x55da9d22b365]
[pkrvmf6wy0o8zjz:65332] *** End of error message ***
</pre>
{% endraw %}
