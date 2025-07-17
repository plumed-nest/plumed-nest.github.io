**Project ID:** [plumID:21.044]({{ '/' | absolute_url }}eggs/21/044/)  
Stderr for source:  driver.dat   
Download: [zipped raw stdout](driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[pkrvmq0rgcvqdmg:09620] *** Process received signal ***
[pkrvmq0rgcvqdmg:09620] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09620] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09620] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4e98845330]
[pkrvmq0rgcvqdmg:09620] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4e9889eb2c]
[pkrvmq0rgcvqdmg:09620] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4e9884527e]
[pkrvmq0rgcvqdmg:09620] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4e988288ff]
[pkrvmq0rgcvqdmg:09620] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4e98ca5ff5]
[pkrvmq0rgcvqdmg:09620] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4e98cbb0da]
[pkrvmq0rgcvqdmg:09620] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4e98ca5a55]
[pkrvmq0rgcvqdmg:09620] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4e98ca5a6f]
[pkrvmq0rgcvqdmg:09620] [ 8] plumed_master(+0x146dd)[0x55baf67826dd]
[pkrvmq0rgcvqdmg:09620] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4e9882a1ca]
[pkrvmq0rgcvqdmg:09620] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4e9882a28b]
[pkrvmq0rgcvqdmg:09620] [11] plumed_master(+0x15365)[0x55baf6783365]
[pkrvmq0rgcvqdmg:09620] *** End of error message ***
</pre>
{% endraw %}
