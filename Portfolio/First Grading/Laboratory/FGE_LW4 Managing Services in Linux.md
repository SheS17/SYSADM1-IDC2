![image](https://github.com/user-attachments/assets/2eb73d4d-0116-4f17-ae55-44723c3ac6cc)


# SYSADM1 -- Managing Services in Linux

# Requirement: 

-   A virtual machine running Linux

![](vertopal_96bc21b0c45e48c2a70de87c62030138/media/image2.png){width="4.135416666666667in"
height="1.8020833333333333in"}

Complete this lab as follows:

1.  Use the service --status-all command to list all active and inactive
    services.

List down active and inactive services in the table below. Provide five
(5) services for each column.

  -----------------------------------------------------------------------
  **Active**                             **Inactive**
  -------------------------------------- --------------------------------
  zfs-zed                                zfs-load-key

  zfs-share                              zfs-import

  zfs-mount                              x11-common

  ufw                                    whoopsie

  unattended-upgrades                    uuidd
  -----------------------------------------------------------------------

SS:

![](vertopal_96bc21b0c45e48c2a70de87c62030138/media/image3.png){width="4.344355861767279in"
height="0.8959590988626421in"}

![](vertopal_96bc21b0c45e48c2a70de87c62030138/media/image4.png){width="4.156829615048119in"
height="1.885680227471566in"}

2.  Start the Bluetooth service using the systemctl command.

Ex. sudo systemctl start httpd

![](vertopal_96bc21b0c45e48c2a70de87c62030138/media/image5.png){width="4.359946412948381in"
height="1.1875in"}

![](vertopal_96bc21b0c45e48c2a70de87c62030138/media/image6.png){width="5.094460848643919in"
height="0.40630686789151355in"}

3.  Check the status of the Bluetooth service. What is its status?

-   **Inactive (dead)**

SS:
![](vertopal_96bc21b0c45e48c2a70de87c62030138/media/image7.png){width="7.027083333333334in"
height="1.4777777777777779in"}

1.  Check the status of the cups services. Since when was it running?

SS:
![](vertopal_96bc21b0c45e48c2a70de87c62030138/media/image8.png){width="7.027083333333334in"
height="3.7493055555555554in"}

-   **It is running since Thu 2024-09-12**

    1.  Stop cups services.

![](vertopal_96bc21b0c45e48c2a70de87c62030138/media/image9.png){width="4.646481846019247in"
height="0.35421587926509185in"}

2.  Verify if the service was stopped.

-   Service stopped

![](vertopal_96bc21b0c45e48c2a70de87c62030138/media/image10.png){width="6.607697944006999in"
height="3.7044641294838145in"}

1.  Restart the cups services

![](vertopal_96bc21b0c45e48c2a70de87c62030138/media/image11.png){width="4.865262467191601in"
height="0.2604527559055118in"}

2.  Verify if the service was restarted.

![](vertopal_96bc21b0c45e48c2a70de87c62030138/media/image12.png){width="7.027083333333334in"
height="3.6034722222222224in"}
