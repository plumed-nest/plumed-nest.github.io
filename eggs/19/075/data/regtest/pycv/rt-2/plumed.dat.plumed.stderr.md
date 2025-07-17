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
[pkrvmq0rgcvqdmg:11701] *** Process received signal ***
[pkrvmq0rgcvqdmg:11701] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11701] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11701] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc9a0845330]
[pkrvmq0rgcvqdmg:11701] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc9a089eb2c]
[pkrvmq0rgcvqdmg:11701] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc9a084527e]
[pkrvmq0rgcvqdmg:11701] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc9a08288ff]
[pkrvmq0rgcvqdmg:11701] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc9a0ca5ff5]
[pkrvmq0rgcvqdmg:11701] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc9a0cbb0da]
[pkrvmq0rgcvqdmg:11701] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc9a0ca5a55]
[pkrvmq0rgcvqdmg:11701] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc9a0ca5a6f]
[pkrvmq0rgcvqdmg:11701] [ 8] plumed(+0x146dd)[0x563f753fc6dd]
[pkrvmq0rgcvqdmg:11701] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc9a082a1ca]
[pkrvmq0rgcvqdmg:11701] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc9a082a28b]
[pkrvmq0rgcvqdmg:11701] [11] plumed(+0x15365)[0x563f753fd365]
[pkrvmq0rgcvqdmg:11701] *** End of error message ***
</pre>
{% endraw %}
