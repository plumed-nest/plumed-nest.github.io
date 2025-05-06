**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1050-229:61430] *** Process received signal ***
[fv-az1050-229:61430] Signal: Aborted (6)
[fv-az1050-229:61430] Signal code:  (-6)
[fv-az1050-229:61430] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f98abc45330]
[fv-az1050-229:61430] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f98abc9eb2c]
[fv-az1050-229:61430] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f98abc4527e]
[fv-az1050-229:61430] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f98abc288ff]
[fv-az1050-229:61430] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f98ac0a5ff5]
[fv-az1050-229:61430] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f98ac0bb0da]
[fv-az1050-229:61430] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f98ac0a5a55]
[fv-az1050-229:61430] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f98ac0a5a6f]
[fv-az1050-229:61430] [ 8] plumed(+0x146dd)[0x55a4b2da06dd]
[fv-az1050-229:61430] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f98abc2a1ca]
[fv-az1050-229:61430] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f98abc2a28b]
[fv-az1050-229:61430] [11] plumed(+0x15365)[0x55a4b2da1365]
[fv-az1050-229:61430] *** End of error message ***
</pre>
{% endraw %}
