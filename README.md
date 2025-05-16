🏙️ Building Extraction from Satellite Imagery using GeoAI 🌍🛰️

🚀 Overview:
This project leverages GeoAI and object detection models to extract buildings from high-resolution satellite imagery. It uses QGIS for creating training samples and geoai-py for model training and inference.

🛠️ Workflow:
  📥 Downloading satellite imagery
  🖊️ Creating training data using QGIS
  🧠 Training object detection models (geoai-py)
  🏗️ Detecting buildings in new satellite images
  📍 Exporting building detections to GeoJSON
  🗺️ Interactive visualization using Leafmap

🖊️ Training Sample Creation in QGIS:
  Open your satellite imagery in QGIS.
  Create a new vector layer (GeoJSON or Shapefile).
  Draw bounding boxes around buildings using the Rectangle tool.
  Save the annotations (make sure to use object class labels).
  Use this file as your input training labels in geoai-py.

🧠 Model Info:
  Supported architectures: YOLOv5, SSD, Faster R-CNN
  Input imagery: RGB GeoTIFF (preferably <1m resolution)
  Training data: GeoJSON or Shapefile with labeled bounding boxes

🔗 Useful Resources:
  🔗 GeoAI Object Detection Docs: https://geoai.gishub.org/examples/train_object_detection_model/
  🗺️ Leafmap: https://leafmap.org
  🗒️ QGIS: https://qgis.org

📜 License:
  MIT License

🏁 Conclusion:
  This project provides an end-to-end pipeline for detecting and extracting buildings from satellite imagery using AI and open-source tools. Ideal for:
    🏗️ Urban Planning
    🚨 Disaster Response
    🧭 Land Use Mapping
    📊 Infrastructure Analysis
