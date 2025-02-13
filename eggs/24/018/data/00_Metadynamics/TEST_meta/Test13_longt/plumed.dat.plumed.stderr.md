**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1280-696:05592] *** Process received signal ***
[fv-az1280-696:05592] Signal: Aborted (6)
[fv-az1280-696:05592] Signal code:  (-6)
[fv-az1280-696:05592] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc1fc845330]
[fv-az1280-696:05592] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc1fc89eb2c]
[fv-az1280-696:05592] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc1fc84527e]
[fv-az1280-696:05592] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc1fc8288ff]
[fv-az1280-696:05592] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc1fcca5ff5]
[fv-az1280-696:05592] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc1fccbb0da]
[fv-az1280-696:05592] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc1fcca5a55]
[fv-az1280-696:05592] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc1fcca5a6f]
[fv-az1280-696:05592] [ 8] plumed(+0x146dd)[0x55cf523f16dd]
[fv-az1280-696:05592] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc1fc82a1ca]
[fv-az1280-696:05592] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc1fc82a28b]
[fv-az1280-696:05592] [11] plumed(+0x15365)[0x55cf523f2365]
[fv-az1280-696:05592] *** End of error message ***
</pre>
{% endraw %}
