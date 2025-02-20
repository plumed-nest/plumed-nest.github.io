**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[fv-az1911-722:09244] *** Process received signal ***
[fv-az1911-722:09244] Signal: Aborted (6)
[fv-az1911-722:09244] Signal code:  (-6)
[fv-az1911-722:09244] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbf58e45330]
[fv-az1911-722:09244] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbf58e9eb2c]
[fv-az1911-722:09244] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbf58e4527e]
[fv-az1911-722:09244] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbf58e288ff]
[fv-az1911-722:09244] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbf592a5ff5]
[fv-az1911-722:09244] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbf592bb0da]
[fv-az1911-722:09244] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbf592a5a55]
[fv-az1911-722:09244] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbf592a5a6f]
[fv-az1911-722:09244] [ 8] plumed(+0x146dd)[0x55e8ae4db6dd]
[fv-az1911-722:09244] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbf58e2a1ca]
[fv-az1911-722:09244] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbf58e2a28b]
[fv-az1911-722:09244] [11] plumed(+0x15365)[0x55e8ae4dc365]
[fv-az1911-722:09244] *** End of error message ***
</pre>
{% endraw %}
