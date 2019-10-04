# Requirement
opencv34

# changed
**1. Depth is not rearranged.** \
ex) depth = m_dTableD2Z[pDepthMap[h][w]]
-> depth = pDepthMap[h][w] \
\
**2. The depth is YUV format, but the content has a z value of type float.**
This has the disadvantage of larger capacity but makes it more accurate when warping.
