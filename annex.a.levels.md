## Annex A: Conformance to video decoders' profiles and levels
{:.no_count}

### General

Profiles and levels of video coding specification specify restrictions on the capabilities 
needed to decode the bitstreams.

The profile specifies the bit depth and subsampling formats supported, while the
level defines resolution and performance characteristics.

### Conformance

A film grain synthesis module compliant to level X.Y of a video decoder must be able to correctly and on time generate 
film grain for all bitstreams (that can be decoded by the general decoding process of the video codec) that conform to that level.

When doing that, the film grain synthesis module must be able to produce output frames according to
the display schedule if such is indicated by the bitstream.

