**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1911-722:09055] *** Process received signal ***
[fv-az1911-722:09055] Signal: Aborted (6)
[fv-az1911-722:09055] Signal code:  (-6)
[fv-az1911-722:09055] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdcde645330]
[fv-az1911-722:09055] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdcde69eb2c]
[fv-az1911-722:09055] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdcde64527e]
[fv-az1911-722:09055] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdcde6288ff]
[fv-az1911-722:09055] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdcdeaa5ff5]
[fv-az1911-722:09055] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdcdeabb0da]
[fv-az1911-722:09055] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdcdeaa5a55]
[fv-az1911-722:09055] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdcdeaa5a6f]
[fv-az1911-722:09055] [ 8] plumed_master(+0x146dd)[0x5576b07ee6dd]
[fv-az1911-722:09055] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdcde62a1ca]
[fv-az1911-722:09055] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdcde62a28b]
[fv-az1911-722:09055] [11] plumed_master(+0x15365)[0x5576b07ef365]
[fv-az1911-722:09055] *** End of error message ***
</pre>
{% endraw %}
