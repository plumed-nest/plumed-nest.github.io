**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[fv-az585-767:10470] *** Process received signal ***
[fv-az585-767:10470] Signal: Aborted (6)
[fv-az585-767:10470] Signal code:  (-6)
[fv-az585-767:10470] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9e23642520]
[fv-az585-767:10470] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f9e236969fc]
[fv-az585-767:10470] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9e23642476]
[fv-az585-767:10470] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f9e236287f3]
[fv-az585-767:10470] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f9e23aa2b9e]
[fv-az585-767:10470] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f9e23aae20c]
[fv-az585-767:10470] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f9e23aae277]
[fv-az585-767:10470] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f9e23aae52b]
[fv-az585-767:10470] [ 8] plumed(+0x14254)[0x562106d21254]
[fv-az585-767:10470] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9e23629d90]
[fv-az585-767:10470] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9e23629e40]
[fv-az585-767:10470] [11] plumed(+0x14eb5)[0x562106d21eb5]
[fv-az585-767:10470] *** End of error message ***
</pre>
{% endraw %}
