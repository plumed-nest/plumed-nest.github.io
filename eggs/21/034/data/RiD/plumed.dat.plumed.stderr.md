**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[fv-az1937-158:65549] *** Process received signal ***
[fv-az1937-158:65549] Signal: Aborted (6)
[fv-az1937-158:65549] Signal code:  (-6)
[fv-az1937-158:65549] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc1c1645330]
[fv-az1937-158:65549] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc1c169eb2c]
[fv-az1937-158:65549] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc1c164527e]
[fv-az1937-158:65549] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc1c16288ff]
[fv-az1937-158:65549] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc1c1aa5ff5]
[fv-az1937-158:65549] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc1c1abb0da]
[fv-az1937-158:65549] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc1c1aa5a55]
[fv-az1937-158:65549] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc1c1aa5a6f]
[fv-az1937-158:65549] [ 8] plumed(+0x146dd)[0x557e3488d6dd]
[fv-az1937-158:65549] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc1c162a1ca]
[fv-az1937-158:65549] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc1c162a28b]
[fv-az1937-158:65549] [11] plumed(+0x15365)[0x557e3488e365]
[fv-az1937-158:65549] *** End of error message ***
</pre>
{% endraw %}
