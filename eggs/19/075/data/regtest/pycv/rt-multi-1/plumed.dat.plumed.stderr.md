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
[fv-az1911-722:09451] *** Process received signal ***
[fv-az1911-722:09451] Signal: Aborted (6)
[fv-az1911-722:09451] Signal code:  (-6)
[fv-az1911-722:09451] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f302b245330]
[fv-az1911-722:09451] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f302b29eb2c]
[fv-az1911-722:09451] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f302b24527e]
[fv-az1911-722:09451] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f302b2288ff]
[fv-az1911-722:09451] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f302b6a5ff5]
[fv-az1911-722:09451] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f302b6bb0da]
[fv-az1911-722:09451] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f302b6a5a55]
[fv-az1911-722:09451] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f302b6a5a6f]
[fv-az1911-722:09451] [ 8] plumed(+0x146dd)[0x56174c2516dd]
[fv-az1911-722:09451] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f302b22a1ca]
[fv-az1911-722:09451] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f302b22a28b]
[fv-az1911-722:09451] [11] plumed(+0x15365)[0x56174c252365]
[fv-az1911-722:09451] *** End of error message ***
</pre>
{% endraw %}
