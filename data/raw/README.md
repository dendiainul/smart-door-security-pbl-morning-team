# Dataset Documentation

## Smart Home IoT Anomaly Detection Dataset
Primary dataset untuk analisis pola keamanan smart door authentication system.

## Dataset Information
- **Source**: Kaggle - Detecting Anomalies in Smart Home IoT Devices
- **URL**: https://www.kaggle.com/datasets/ministerjohn/detecting-anomalies-in-smart-home-iot-devices
- **Description**: Network traffic data dari smart home IoT devices untuk anomaly detection
- **Size**: 1.11 MB (manageable untuk development)
- **Format**: CSV dengan 10+ features + anomaly labels
- **Context**: Smart home cybersecurity dengan focus pada Smart Lock devices

## Key Features untuk Smart Door Analysis

### Core Fields:
- **Timestamp**: Time-based pattern analysis (jam rawan detection)
- **Device_Type**: "Smart Lock" devices - perfect match untuk smart door
- **Activity**: Door operations dan network activities
- **Label**: Normal/Anomaly classification untuk supervised learning

### Network Analysis Fields:
- **Src_IP/Dst_IP**: User device komunikasi dengan door system
- **Src_Port/Dst_Port**: Communication channel analysis
- **Protocol**: TCP/UDP security protocol analysis
- **Packet_Size**: Data transfer pattern analysis
- **Flags**: Network packet control flags
- **Payload**: Data transmission analysis

## Indonesian Context Integration
- **Working hours analysis**: 8-17 WIB pattern extraction dari timestamps
- **Cultural patterns**: Weekend vs weekday access behavior
- **Jam rawan detection**: 00:00-04:59 anomaly analysis
- **Local threat scenarios**: Indonesian-specific security patterns

## Algorithm Applications
- **Isolation Forest**: Detect unusual packet sizes dan timing patterns
- **Random Forest**: Classify normal vs anomaly menggunakan semua features
- **K-Means Clustering**: Segment different types of smart lock activities

## Team Responsible
- **Dataset Download & Setup**: navitadamayantisyarif
- **IoT Context Adaptation**: thariq24  
- **Smart Door Mapping**: geannnnn
