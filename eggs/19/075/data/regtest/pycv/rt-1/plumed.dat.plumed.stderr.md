**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1911-722:09039] *** Process received signal ***
[fv-az1911-722:09039] Signal: Aborted (6)
[fv-az1911-722:09039] Signal code:  (-6)
[fv-az1911-722:09039] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2217845330]
[fv-az1911-722:09039] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f221789eb2c]
[fv-az1911-722:09039] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f221784527e]
[fv-az1911-722:09039] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f22178288ff]
[fv-az1911-722:09039] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2217ca5ff5]
[fv-az1911-722:09039] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2217cbb0da]
[fv-az1911-722:09039] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2217ca5a55]
[fv-az1911-722:09039] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2217ca5a6f]
[fv-az1911-722:09039] [ 8] plumed(+0x146dd)[0x55a70c6c06dd]
[fv-az1911-722:09039] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f221782a1ca]
[fv-az1911-722:09039] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f221782a28b]
[fv-az1911-722:09039] [11] plumed(+0x15365)[0x55a70c6c1365]
[fv-az1911-722:09039] *** End of error message ***
</pre>
{% endraw %}
