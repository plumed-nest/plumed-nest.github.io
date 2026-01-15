**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervmmtnos:34478] *** Process received signal ***
[runnervmmtnos:34478] Signal: Aborted (6)
[runnervmmtnos:34478] Signal code:  (-6)
[runnervmmtnos:34478] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7eff6aa45330]
[runnervmmtnos:34478] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7eff6aa9eb2c]
[runnervmmtnos:34478] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7eff6aa4527e]
[runnervmmtnos:34478] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7eff6aa288ff]
[runnervmmtnos:34478] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7eff6aea5ff5]
[runnervmmtnos:34478] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7eff6aebb0da]
[runnervmmtnos:34478] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7eff6aea5a55]
[runnervmmtnos:34478] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7eff6aea5a6f]
[runnervmmtnos:34478] [ 8] plumed(+0x146dd)[0x55c5086836dd]
[runnervmmtnos:34478] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7eff6aa2a1ca]
[runnervmmtnos:34478] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7eff6aa2a28b]
[runnervmmtnos:34478] [11] plumed(+0x15365)[0x55c508684365]
[runnervmmtnos:34478] *** End of error message ***
</pre>
{% endraw %}
