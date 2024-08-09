**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az840-554:05739] *** Process received signal ***
[fv-az840-554:05739] Signal: Aborted (6)
[fv-az840-554:05739] Signal code:  (-6)
[fv-az840-554:05739] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8b87c42520]
[fv-az840-554:05739] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8b87c969fc]
[fv-az840-554:05739] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8b87c42476]
[fv-az840-554:05739] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8b87c287f3]
[fv-az840-554:05739] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f8b880a2b9e]
[fv-az840-554:05739] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f8b880ae20c]
[fv-az840-554:05739] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f8b880ae277]
[fv-az840-554:05739] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8b880ae52b]
[fv-az840-554:05739] [ 8] plumed_master(+0x14274)[0x55fc02b0c274]
[fv-az840-554:05739] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8b87c29d90]
[fv-az840-554:05739] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8b87c29e40]
[fv-az840-554:05739] [11] plumed_master(+0x14ed5)[0x55fc02b0ced5]
[fv-az840-554:05739] *** End of error message ***
</pre>
{% endraw %}
