![](header.png)

<h1 align="center">Hi, I'm Usman 😃</h1>

<p align='center'>
<a href="https://www.linkedin.com/in/usmanmehmood55/"><img height="30" src="linkedin.png"></a>
</p>

I'm an Embedded Software Engineer. Graduated from [Air University Islamabad](https://www.au.edu.pk/) 
with bachelors in Mechatronics Engineering.

I've got 3+ years of experience in embedded software, IoT systems, PCB design, and CAD design. I 
also occasionally develop .NET WPF and backend applications. And recently I have started writing
in JavaScript as well.

```c
summary_t professional_summary(person_t me)
{
    return (summary_t)
    {
        .person              = me,

        .embedded_software   =
        {
            .time            = (years_t)3,
            .catagories      = { DRIVERS, LOW_POWER, THREAD, BLE, MESH, MOTOR_CTRL },
            .processor_types = { ARM, RISC_V, XTENSA },
            .frameworks      = { ESP_IDF, FREE_RTOS, NRF_CONNECT_SDK, ZEPHYR, LINUX },
            .misra_compliant = true,
            .test_driven     = true,
            .documented      = EXCESSIVELY,
            .philosophy      = "If the code aint vibing, I aint typing",
            .languages_used  = { C, CSHARP },
            .sometimes_used  = { CPP, RUST, JAVASCRIPT },

            .is_python_used  = false,
            .but_why_tho     = malloc(&NULL * -1 << UINT128_MAX),
        },

        .embedded_hardware   = 
        {
            .time            = (years_t)4,
            .catagories      = { POWER, MOTOR_CTRL, AMPS, ENRGY_HARVST, WIRELESS },
            .multilayer_pcbs = true,
            .preferred_eda   = KICAD,
        },

        .mechanical_design   =
        {
            .time            = (years_t)2,
            .catagories      = { ROBOT_CHASSIS, ENCLOSURES, SIMULATIONS, ANIMATIONS, RENDERING },
            .preferred_cad   = { SOLIDWORKS, SW_VISUALIZE, KEYSHOT },
            .wasted_skill    = 
            {
                MATHEMATICAL_MODELING, VIBRATION_ANALYSIS,
                FLUID_ANALYSIS, CONTROL_SYSTEMS, ROBOTICS 
            },
            .regret          = true,
        }
    }
}
```