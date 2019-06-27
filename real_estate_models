#Residental Real Estate - NYC

#consider https://www1.nyc.gov/assets/finance/jump/hlpbldgcode.html
#This is NYCs official classification of all buildings

#important realtor service::!!
#Multiple Listing Services (MLS)
##redfin has access to this as a data source

#studio Apt
#1-3 br Apt
#Townhomes <class A7>

##idea:
#try to predict rent (or property sale price) using pictures of properties

property ={
    "interior":{
        "IMG":{
            "kitchen":None,
            "bathroom":None,
            "living room":None,
            "bedroom":None,
            "dining room":None,
            "interior":None
            },
        "META":{
            "sqft":None,
            "#bed":None,
            "#bath":None,
            "age":None
            }
    },
    "exterior":{
        "IMG":{
            "exterior":None,
            "satellite":None
        },
        "LOCATION":{
            "address":None,
            "long":None,
            "lat":None
            }
    }
}

#previous works:
#<1> https://arxiv.org/pdf/1611.09180.pdf
##tools they use are RNN (recurrent neural net) and CNN (convolutional neural net)

#distinction between house intrinsic features and extrinsic features

#Intrinsic features
##home meta data
# --number of beds, baths, etc`
# --images of interior

#extrinsic features
##location
# --neighborhood
# --traffic
# --schools
# --amenities

#if Home i and Home j are in the same neighborhood, they will have THE SAME extrinsic features
##even if they have different intrinsic features


#<2> https://arxiv.org/pdf/1808.02547.pdf
#github link
##https://npm.pkg.github.com/denadai2/real-estate-neighborhood-prediction


#<3> Image based analysis
#https://omidpoursaeed.github.io/publication/vision-based-real-estate-price-estimation/
#https://link.springer.com/epdf/10.1007/s00138-018-0922-2?author_access_token=bjT1UiXuEmZK6G2RWmHKjPe4RwlQNchNByi7wbcMAY4nJMkzJvUFElXbphcDehx2Hme5PDwiuu5v0Fh50rgZx2ier4WLTekZ_dKXpuGPb-8YE-0PfejyF3Z3Y8R9GgR4p2jgUv7EPsXbI7-yH0x7Og%3D%3D
# -- goal: encode the "luxury level" of collections of dwelling photos using CNNs


#<4> Yann Lecunn Paper
#http://yann.lecun.com/exdb/publis/pdf/chopra-kdd-07.pdf
