**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[fv-az816-356:07341] *** Process received signal ***
[fv-az816-356:07341] Signal: Aborted (6)
[fv-az816-356:07341] Signal code:  (-6)
[fv-az816-356:07341] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f513e245330]
[fv-az816-356:07341] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f513e29eb2c]
[fv-az816-356:07341] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f513e24527e]
[fv-az816-356:07341] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f513e2288ff]
[fv-az816-356:07341] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f513e6a5ff5]
[fv-az816-356:07341] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f513e6bb0da]
[fv-az816-356:07341] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f513e6a5a55]
[fv-az816-356:07341] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f513e6a5a6f]
[fv-az816-356:07341] [ 8] plumed(+0x146dd)[0x5589ab1b76dd]
[fv-az816-356:07341] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f513e22a1ca]
[fv-az816-356:07341] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f513e22a28b]
[fv-az816-356:07341] [11] plumed(+0x15365)[0x5589ab1b8365]
[fv-az816-356:07341] *** End of error message ***
</pre>
{% endraw %}
