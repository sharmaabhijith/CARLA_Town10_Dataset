# CARLA Town 10 Dataset

![Sample image frames from the CART (CARLA Town 10) dataset. Town 10 is the HD map in CARLA, replicating realistic scenarios](static/images/catt.png)

## Dataset Description
The CARLA Town 10 Dataset is a photo-realistic dataset created using the CARLA simulator in Town 10. This dataset is designed for tasks like object detection, autonomous driving research, and adversarial testing. Below are the key details:

- **Total Images**: 4500 (Train: ~4300, Validation: ~200)
- **Image Resolution**: 1280×720 pixels
- **Classes**:
  - Person
  - Vehicle
  - Motorbike
  - Traffic Light
  - Stop Sign
- **Scenario**: 
  - Data collected using autopilot driving in CARLA's Town 10, featuring a moving camera.
- **Environmental Diversity**:
  - Lighting: Noon, Sunset, Night
  - Weather: Rain, Clear, Fog
- **Traffic Level**:
  - Moderate traffic with approximately 40 vehicles and 70 pedestrians in the map.
- **Annotations**:
  - Labels available in YOLO format.
  - Annotations performed using the [CVAT tool](https://www.cvat.ai/).

This dataset has been utilized in the original research paper to train the YOLOv5 model and test adversarial patches.

---

## Citation
If you find our dataset useful in your research, please consider citing our work:

```bibtex
@article{sharma2024avatar,
      title={AVATAR: Autonomous Vehicle Assessment through Testing of Adversarial Patches in Real-time},
      author={Sharma, Abhijith and Narayan, Apurva and Azad, Nasser Lashgarian and Fischmeister, Sebastian and Marksteiner, Stefan},
      journal={IEEE Transactions on Intelligent Vehicles},
      year={2024},
      publisher={IEEE}
    }
