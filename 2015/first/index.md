<head><title>SOLVCON Seminar</title></head>

# SOLVCON Seminar

## December 8, 2015, Tuesday

* Where: [Mozille Community Space Taipei](https://moztw.org/space/)
* When: 18:30-20:30
* This event will be held together with
  [Taipei Open Source Software User Group (TOSSUG)](http://www.tossug.org/)

## Agenda

| Time          | Topic                                 | Speaker        |
| :------------ | :------------------------------------ | :------------- |
| 18:30 - 18:45 | Chat                                  |                |
| 18:45 - 19:15 | [SOLVCON Mesh](#mesh)                 | Yung-Yu Chen   |
| 19:15 - 19:45 | [As a beginner](#beginner)            | You-Hao Chang  |
| 19:45 - 20:15 | [Design of the Probe Feature](#probe) | Taihsiang Ho   |
| 20:15 - 20:30 | Wrap-up                               |                |

## Abstract

### <a name="mesh"></a> SOLVCON Mesh

By [Yung-Yu Chen](mailto:yyc@solvcon.net)

This talk introduces the data structures of the unstructured mesh in SOLVCON.
The unstructured mesh of mixed elements use lookup tables. The speaker will
show the constructs of the data structures, and how to use them to represent
and manipulate the data. In addition, because SOLVCON uses domain decomposition
for parallel computing, the speaker will explain how to use a graph partitioner
to separate the globally connected mesh and minimize the inter-connection
between split domains.

###<a name="beginner"></a> As a beginner

By You-Hao Chang

In the beginning of being a contributor, it is always useful for people to 
know what kind of background knowledge we shall have. This talk will focus 
on introducing the pre-work of contributing SOLVCON and also show plenty of
 material for learning the numerical field.

### <a name="probe"></a> Design of the Probe Feature

By Taihsiang Ho

The probe feature could only dump the physics data at the end of the whole
march. This talk is going to introduce how the current probe feature to fit the
current loop structure of the march, and what is the possible roadmap to
enhance this feature.
