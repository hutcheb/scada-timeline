# Development of SCADA systems

```mermaid
---
title: Development of SCADA systems
---
gantt
    dateFormat YYYY
    section Rockwell
        %%(https://www.plctalk.net/threads/factorytalk-rsview-product-history.127108/)
        Advisor PC : advisorpc, 1982, 2000
        ControlView : controlview, 1987, 1997
        RsView32    :1997, 2009
        RSView Enterprise : 2005, 2012
        Factory Talk View SE :2012, until 2025
        FactoryTalk Optix    : 2022, until 2025
    section Citect Technologies
        %%(https://en.wikipedia.org/wiki/Citect)
        CitectSCADA :c1, 1973, 2006
    section Invensys plc
        %%(https://en.wikipedia.org/wiki/Wonderware)
        Wonderware :s2, 1987, 2014
    section AVEVA/Schneider
        CitectSCADA :after c1, 2020
        PlantSCADA :until 2025
        System Platform :after s2, until 2025
        %%(Don't have dates for Intouch)
        AVEVA Intouch HMI :after s2, until 2025
        %%(https://github.com/hutcheb/scada-timeline/issues/1)
        SCX6 : scx6, 2000, 2010
        ClearSCADA :clearscada, after scx6, 2018
        Geo SCADA Expert : after clearscada, until 2025
    section Honeywell
        %%(Estimates)
        PlantScape :plantscape, 1995, 2005
        Experion PKS: after plantscape, until 2025
    section ABB
        %%(https://de.wikipedia.org/wiki/800xA)
        Ability System 800xA : 2002, until 2025
    section Inductive Automation
        %%(https://en.wikipedia.org/wiki/Inductive_Automation)
        FactoryPMI : factorypmi, 2003, 2010
        Ignition :ignition, after factorypmi, until 2025
    section Iconics
        %%(https://en.wikipedia.org/wiki/Iconics)
        Genesis :genesis, 1986, 2011
    section Mitsubishi
        Genesis :after genesis, until 2025
    section UGS Corporation
        %%(https://drivesncontrols.com/siemens-ends-development-of-factorylink/)
        FactoryLink : factorylink, 1978, 2007
    section Siemens
        FactoryLink : after factorylink, 2009
        %%(https://en.wikipedia.org/wiki/WinCC)
        WinCC :siemens1, 1996, until 2025
        WinCC OA :winccoa, 2023, until 2025
    section Intellution
        %%(https://de.wikipedia.org/wiki/Proficy_iFIX)
        iFix : intellutionfix, 1984, 2002
    section GE
        iFix : after intellutionfix, until 2025
        %%(https://en.wikipedia.org/wiki/GE_Digital)
        Cimplicity :cimplicity, 1995, until 2025
    section Emerson
        %%(No idea)
        DeltaV : 1990, 30y
        %%(Estimate)
        Movicon Next : 2012, until 2025
    section Yokogawa 
        %%(No idea)
        ProSafe-RS: : 1990, 30y
        FAST/TOOLS : 1990, 30y
    section Weatherford
        %%(https://www.weatherford.com/products-and-services/production-and-intervention/production-4-0/iot-scada-platform/)
        %%(No idea)
        Cygnet : 1990, 30y
    section Trihedral
        %%(https://en.wikipedia.org/wiki/Trihedral_Engineering)
        WEB : web, 1988, 1997
        Visual Tag System : vts, after web, 2007
        VTScada : after vts, until 2025
    section eLynx Technologies
        %%(https://www.elynxtech.com/company/about) 
        eLynx  : 2000, until 2025
    section Wizcon Systems 
        %%(https://www.wizconscada.com/)
        Wizcon  : 1980, 2008    
        %%(https://elutions-controlmaestro.com/ourcompany/)
        ControlMaestro : 2008, until 2025
    
    section Open Source
        %%(https://en.wikipedia.org/wiki/EPICS)
        EPICS : epics, 1994, until 2025
        %%(https://en.wikipedia.org/wiki/TANGO)
        TANGO : tango, 2001, until 2025
        %%(https://github.com/RapidScada/scada/graphs/code-frequency)
        RapidSCADA : rapidscada, 2014, until 2025
        %%(https://github.com/SCADA-LTS/Scada-LTS/graphs/code-frequency)
        SCADA-LTS : scada-lts, 2016, until 2025
        %%(https://github.com/pyscada/PyScada/graphs/code-frequency)
        PySCADA : pyscasa, 2013, until 2025
        %%(https://github.com/riclolsen/json-scada/graphs/code-frequency)
        json.scada : jsonscada, 2020, until 2025
        %%(https://github.com/frangoteam/FUXA/graphs/code-frequency)
        FUXA : fuxa, 2019, until 2025
        
```

## Status
I have provided references for most of them, some of the Yokogawa and Emerson stuff I wasn't able to find any information on.
The wiki references were easy, ideally there would be proper references from each company.

## Contribution
Please feel free to raise a PR or Issue to get it updated. Always looking for help.