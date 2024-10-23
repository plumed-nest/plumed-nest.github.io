**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[fv-az585-767:10478] *** Process received signal ***
[fv-az585-767:10478] Signal: Aborted (6)
[fv-az585-767:10478] Signal code:  (-6)
[fv-az585-767:10478] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbc2b842520]
[fv-az585-767:10478] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbc2b8969fc]
[fv-az585-767:10478] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbc2b842476]
[fv-az585-767:10478] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbc2b8287f3]
[fv-az585-767:10478] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fbc2bca2b9e]
[fv-az585-767:10478] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fbc2bcae20c]
[fv-az585-767:10478] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fbc2bcae277]
[fv-az585-767:10478] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fbc2bcae52b]
[fv-az585-767:10478] [ 8] plumed_master(+0x14254)[0x55cb0f516254]
[fv-az585-767:10478] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbc2b829d90]
[fv-az585-767:10478] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbc2b829e40]
[fv-az585-767:10478] [11] plumed_master(+0x14eb5)[0x55cb0f516eb5]
[fv-az585-767:10478] *** End of error message ***
</pre>
{% endraw %}
