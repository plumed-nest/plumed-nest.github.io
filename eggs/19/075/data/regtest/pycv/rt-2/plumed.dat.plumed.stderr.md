**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az585-767:10408] *** Process received signal ***
[fv-az585-767:10408] Signal: Aborted (6)
[fv-az585-767:10408] Signal code:  (-6)
[fv-az585-767:10408] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2152c42520]
[fv-az585-767:10408] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f2152c969fc]
[fv-az585-767:10408] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2152c42476]
[fv-az585-767:10408] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f2152c287f3]
[fv-az585-767:10408] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f21530a2b9e]
[fv-az585-767:10408] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f21530ae20c]
[fv-az585-767:10408] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f21530ae277]
[fv-az585-767:10408] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f21530ae52b]
[fv-az585-767:10408] [ 8] plumed(+0x14254)[0x557ff693d254]
[fv-az585-767:10408] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2152c29d90]
[fv-az585-767:10408] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2152c29e40]
[fv-az585-767:10408] [11] plumed(+0x14eb5)[0x557ff693deb5]
[fv-az585-767:10408] *** End of error message ***
</pre>
{% endraw %}
