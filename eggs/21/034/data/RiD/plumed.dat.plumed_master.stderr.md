**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervmkj6or:07618] *** Process received signal ***
[runnervmkj6or:07618] Signal: Aborted (6)
[runnervmkj6or:07618] Signal code:  (-6)
[runnervmkj6or:07618] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb3f7245330]
[runnervmkj6or:07618] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb3f729eb2c]
[runnervmkj6or:07618] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb3f724527e]
[runnervmkj6or:07618] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb3f72288ff]
[runnervmkj6or:07618] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb3f76a5ff5]
[runnervmkj6or:07618] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb3f76bb0da]
[runnervmkj6or:07618] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb3f76a5a55]
[runnervmkj6or:07618] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb3f76a5a6f]
[runnervmkj6or:07618] [ 8] plumed_master(+0x146dd)[0x55cf757346dd]
[runnervmkj6or:07618] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb3f722a1ca]
[runnervmkj6or:07618] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb3f722a28b]
[runnervmkj6or:07618] [11] plumed_master(+0x15365)[0x55cf75735365]
[runnervmkj6or:07618] *** End of error message ***
</pre>
{% endraw %}
