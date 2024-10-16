# Face Verification Project

## Description
This project focuses on verifying faces using three popular datasets: LFW (Labeled Faces in the Wild), FaceScrub, and CelebA. The goal is to build a robust face verification system that can accurately identify and verify faces across these datasets.

## Datasets
- **LFW (Labeled Faces in the Wild)**: A dataset of face photographs designed for studying the problem of unconstrained face recognition (download it [here](https://vis-www.cs.umass.edu/lfw/)).
- **CelebA**: A large-scale face attributes dataset with more than 200,000 celebrity images, each with 40 attribute annotations (download it [here](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)).

## Installation
To set up the project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yovannynogales/face-verification-project.git
    cd face-verification-project
    ```

2. Create a virtual environment and activate it:
    ```sh
    conda create --name pattern-recognition-project python=3.11
    conda activate pattern-recognition-project
    ```

3. Install the required packages:
    ```sh
    conda install matplotlib
    conda install pandas
    conda install numpy
    conda install scikit-learn
    ```

## Structure of Data folder
 - celeba-dataset/
    - dataset-attributes.pkl
    - identity_CelebA.txt
    - img_align_celeba/
      - 000001.jpg
      - 000002.jpg
      - ...
    - list_attr_celeba.txt
    - list_bbox_celeba.txt
    - list_eval_partition.txt
    - list_landmarks_align_celeba.txt
    - list_landmarks_celeba.txt
  - facescrub-dataset/
    - facescrub_actors.txt
    - facescrub_actresses.txt
    - images/
      - actor1/
        - image1.jpg
        - image2.jpg
        - ...
      - actor2/
        - image1.jpg
        - image2.jpg
        - ...
  - lfw-dataset/
    - lfw_attributes.txt
    - lfw_people.txt
    - images/
      - person1/
        - image1.jpg
        - image2.jpg
        - ...
      - person2/
        - image1.jpg
        - image2.jpg
        - ...

## Contributing
We welcome contributions to improve this project. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```sh
    git commit -m "Description of changes"
    ```
4. Push to the branch:
    ```sh
    git push origin feature-branch
    ```
5. Create a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.