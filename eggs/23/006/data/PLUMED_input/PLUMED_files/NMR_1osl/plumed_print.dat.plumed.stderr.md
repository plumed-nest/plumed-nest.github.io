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
[runnervm0kj6c:07055] *** Process received signal ***
[runnervm0kj6c:07055] Signal: Aborted (6)
[runnervm0kj6c:07055] Signal code:  (-6)
[runnervm0kj6c:07055] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f448fa45330]
[runnervm0kj6c:07055] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f448fa9eb2c]
[runnervm0kj6c:07055] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f448fa4527e]
[runnervm0kj6c:07055] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f448fa288ff]
[runnervm0kj6c:07055] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f448fea5ff5]
[runnervm0kj6c:07055] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f448febb0da]
[runnervm0kj6c:07055] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f448fea5a55]
[runnervm0kj6c:07055] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f448fea5a6f]
[runnervm0kj6c:07055] [ 8] plumed(+0x146dd)[0x55ea110af6dd]
[runnervm0kj6c:07055] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f448fa2a1ca]
[runnervm0kj6c:07055] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f448fa2a28b]
[runnervm0kj6c:07055] [11] plumed(+0x15365)[0x55ea110b0365]
[runnervm0kj6c:07055] *** End of error message ***
</pre>
{% endraw %}
