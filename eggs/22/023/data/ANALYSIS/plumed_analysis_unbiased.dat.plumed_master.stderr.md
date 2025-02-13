**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az1390-170:09345] *** Process received signal ***
[fv-az1390-170:09345] Signal: Aborted (6)
[fv-az1390-170:09345] Signal code:  (-6)
[fv-az1390-170:09345] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fecd0845330]
[fv-az1390-170:09345] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fecd089eb2c]
[fv-az1390-170:09345] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fecd084527e]
[fv-az1390-170:09345] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fecd08288ff]
[fv-az1390-170:09345] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fecd0ca5ff5]
[fv-az1390-170:09345] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fecd0cbb0da]
[fv-az1390-170:09345] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fecd0ca5a55]
[fv-az1390-170:09345] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fecd0ca5a6f]
[fv-az1390-170:09345] [ 8] plumed_master(+0x146dd)[0x55556f6c16dd]
[fv-az1390-170:09345] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fecd082a1ca]
[fv-az1390-170:09345] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fecd082a28b]
[fv-az1390-170:09345] [11] plumed_master(+0x15365)[0x55556f6c2365]
[fv-az1390-170:09345] *** End of error message ***
</pre>
{% endraw %}
