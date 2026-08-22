**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[runnervm76f27:08618] *** Process received signal ***
[runnervm76f27:08618] Signal: Aborted (6)
[runnervm76f27:08618] Signal code:  (-6)
[runnervm76f27:08618] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd65a645330]
[runnervm76f27:08618] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd65a69ec0c]
[runnervm76f27:08618] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd65a64527e]
[runnervm76f27:08618] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd65a6288ff]
[runnervm76f27:08618] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd65aaa5ff5]
[runnervm76f27:08618] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd65aabb0da]
[runnervm76f27:08618] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd65aaa5a55]
[runnervm76f27:08618] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd65aaa5a6f]
[runnervm76f27:08618] [ 8] plumed_master(+0x146dd)[0x562520dc26dd]
[runnervm76f27:08618] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd65a62a1ca]
[runnervm76f27:08618] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd65a62a28b]
[runnervm76f27:08618] [11] plumed_master(+0x15365)[0x562520dc3365]
[runnervm76f27:08618] *** End of error message ***
</pre>
{% endraw %}
