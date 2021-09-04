# CP-Vton-cloth-masking
Classification , Parsing and Virtual Try On clothes


For more detail of the problem, check AI hackathon 2020 pdf 


We are working on a major design project in the area of a Image-based virtual try-on platform for Virtual Try-on of clothes which uses machine learning based mathematical models and physical transformation for draping, wrapping, resizing and shadow creation of clothes. The project is being done as a part of winter internship as ML engineer at ShopCom now Wobb.in (unit of Ravgins International Pvt Ltd). Our external supervisor on the project is Mr Ishan Jindal, ex-IITD alumnus who is Managing Director of this start-up company.

Wobb is a budding startup based in Gurugram and founded by a group of IITD alumni. Wobb is an influencer marketing platform revolutionising advertisement tech through AI and Computation. Our work as an intern there was to help build the Virtual Try On model to optimize Brands engagement with Influencers for driving superior customer engagement and sales.

The more detailed description of the project is given below

Recent years have witnessed the increasing demands of online shopping for fashion items. Despite the convenience online fashion shopping provides, consumers are concerned about how a particular fashion item in a product image would look on them when buying apparel online. Thus, allowing consumers to virtually try on clothes will not only enhance their shopping experience, transforming the way people shop for clothes, but also save cost for retailers. Our goal is to synthesize a photo-realistic new image by overlaying a product image seamlessly onto the corresponding region of a clothed person.
The synthetic image is expected to be perceptually convincing, meeting the following criteria:
(1) body parts and pose of the person are the same as in the original image
(2) the clothing item in the product image deforms naturally
(3) detailed visual patterns of the desired product are clearly visible, which include not only low-level features


We have successfully implemented and able to do all 3 points. 
Our work was based on a research paper named CP-VTON (Characteristics Preserving Virtual Try On) and was further improved modifying the Try On Module (TOM).

CP-VTON learns a thin-plate spline (TPS) transformation for transforming the in-shop clothes into fitting the body shape of the target person via a new Geometric Matching Module (GMM). Second, to alleviate boundary artifacts of warped clothes and make the results more realistic, we employs a Try-On Module that learns a composition mask to integrate the warped clothes and the rendered image to ensure smoothness. The image is processed to remove background to get clipped image of clothes only, and deep learning is used to do step training for resizing and fitting the cloth to the size of body torso. Finer training of machine learning model is  done for local draping, wrapping, and shadow module so that proper shadow and wrinkles are created and superimposed image does not look synthetic.  The platform uses Python based ML framework for development. 



