**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[fv-az1267-279:66123] *** Process received signal ***
[fv-az1267-279:66123] Signal: Aborted (6)
[fv-az1267-279:66123] Signal code:  (-6)
[fv-az1267-279:66123] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2433a45330]
[fv-az1267-279:66123] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2433a9eb2c]
[fv-az1267-279:66123] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2433a4527e]
[fv-az1267-279:66123] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2433a288ff]
[fv-az1267-279:66123] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2433ea5ff5]
[fv-az1267-279:66123] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2433ebb0da]
[fv-az1267-279:66123] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2433ea5a55]
[fv-az1267-279:66123] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2433ea5a6f]
[fv-az1267-279:66123] [ 8] plumed(+0x146dd)[0x55f792d796dd]
[fv-az1267-279:66123] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2433a2a1ca]
[fv-az1267-279:66123] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2433a2a28b]
[fv-az1267-279:66123] [11] plumed(+0x15365)[0x55f792d7a365]
[fv-az1267-279:66123] *** End of error message ***
</pre>
{% endraw %}
