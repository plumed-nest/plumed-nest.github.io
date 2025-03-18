**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az1267-279:64495] *** Process received signal ***
[fv-az1267-279:64495] Signal: Aborted (6)
[fv-az1267-279:64495] Signal code:  (-6)
[fv-az1267-279:64495] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0589645330]
[fv-az1267-279:64495] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f058969eb2c]
[fv-az1267-279:64495] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f058964527e]
[fv-az1267-279:64495] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f05896288ff]
[fv-az1267-279:64495] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0589aa5ff5]
[fv-az1267-279:64495] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0589abb0da]
[fv-az1267-279:64495] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0589aa5a55]
[fv-az1267-279:64495] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0589aa5a6f]
[fv-az1267-279:64495] [ 8] plumed(+0x146dd)[0x5640127626dd]
[fv-az1267-279:64495] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f058962a1ca]
[fv-az1267-279:64495] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f058962a28b]
[fv-az1267-279:64495] [11] plumed(+0x15365)[0x564012763365]
[fv-az1267-279:64495] *** End of error message ***
</pre>
{% endraw %}
