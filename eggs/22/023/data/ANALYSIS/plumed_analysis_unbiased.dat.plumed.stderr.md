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
[fv-az805-507:11383] *** Process received signal ***
[fv-az805-507:11383] Signal: Aborted (6)
[fv-az805-507:11383] Signal code:  (-6)
[fv-az805-507:11383] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faac2245330]
[fv-az805-507:11383] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faac229eb2c]
[fv-az805-507:11383] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faac224527e]
[fv-az805-507:11383] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faac22288ff]
[fv-az805-507:11383] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faac26a5ff5]
[fv-az805-507:11383] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faac26bb0da]
[fv-az805-507:11383] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faac26a5a55]
[fv-az805-507:11383] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faac26a5a6f]
[fv-az805-507:11383] [ 8] plumed(+0x146dd)[0x55aaf2bcd6dd]
[fv-az805-507:11383] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faac222a1ca]
[fv-az805-507:11383] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faac222a28b]
[fv-az805-507:11383] [11] plumed(+0x15365)[0x55aaf2bce365]
[fv-az805-507:11383] *** End of error message ***
</pre>
{% endraw %}
