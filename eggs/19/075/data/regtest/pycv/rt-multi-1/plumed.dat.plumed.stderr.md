**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az585-767:10628] *** Process received signal ***
[fv-az585-767:10628] Signal: Aborted (6)
[fv-az585-767:10628] Signal code:  (-6)
[fv-az585-767:10628] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f41f9642520]
[fv-az585-767:10628] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f41f96969fc]
[fv-az585-767:10628] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f41f9642476]
[fv-az585-767:10628] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f41f96287f3]
[fv-az585-767:10628] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f41f9aa2b9e]
[fv-az585-767:10628] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f41f9aae20c]
[fv-az585-767:10628] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f41f9aae277]
[fv-az585-767:10628] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f41f9aae52b]
[fv-az585-767:10628] [ 8] plumed(+0x14254)[0x563471bd8254]
[fv-az585-767:10628] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f41f9629d90]
[fv-az585-767:10628] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f41f9629e40]
[fv-az585-767:10628] [11] plumed(+0x14eb5)[0x563471bd8eb5]
[fv-az585-767:10628] *** End of error message ***
</pre>
{% endraw %}
