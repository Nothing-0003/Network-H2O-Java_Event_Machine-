# Network-H2O-Java_Event_Machine-
A Network Simulator From Scratch With Java. With An Event Stat Machine, To Model All Network And Nodes To Represent An Event Stat. More Will Be Clarify With The Help Of Code Itself

                          #########################################################
                          ***********EVENT BASED JAVA NETWORK SIMULATOR***********
                          #########################################################

Honestly, To Making Just A Network Simulator Is Other From Scratch Is Other Thing, But to Model Something (Especially, Like A Network Simulator) Into Something Like Event Machine Is Far Beyond Just A Beginner Level.

Let's Differentiate A Regular Network Simulator And My Idea About Event Driven Network Stat Machine.

    Regular Network Simulator :

    ###############################################
    #*********************************************#
    #|Router-Code|Switch-Code|Pc-Code|Server-Code|# <-----Objects And Their Code Here
    #*********************************************#
    #|packet-field|addresses|data|checksum|time|**# <-----Actual Packet Here
    #*********************************************#
    #|Firewall|Polices|Authentication|Keys|Logs|**# <-----Security Here
    #*********************************************#
    #|If-else|List|Data_Structure|Database|*******# <-----Packet Processing Logic Here
    #*********************************************#
    ###############################################

    Event Driven Network Simulator :

    ###############################################
    #||*************||*************||***********||#
    #||*************||Event_Tracker||***********||# <---Security Policy Here
    #||*************||*************||***********||#
    #||*************||Event_interfc||***********||# <-- Both Packet And Network Objects Here (All As Stat Machine)
    #||*************||*************||***********||#
    #||*************||Event_Manager||***********||# <---Packet Processing Here
    #||*************||*************||***********||# 
    ###############################################

    
