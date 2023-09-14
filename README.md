# Express_Api
USER ROUTES.................. 1- router.post('/signup', SignUp) 2- router.post('/login', loginUser) 3- router.get('/allusers', getAllUsers) 4- router.get('/userbyemail/:email', getUserbyEmail) 5- router.put('/updateuser/:id', updateUserById)

PRODUCT ROUTES............................... 1- router.post('/products', postProducts); 2- router.get('/getproduct', getProduct); 3- router.get('/getproductbycategory', getProductByCategory); 4- router.get('/getproductbybrand', getProductByBrand); 5- router.get('/allproducts',getAllProducts) 6- router.get('/getproductbyid/:_id', getProductById); 7- router.put('/updateproduct', updateProduct); 8- router.delete('/deleteproduct/:_id', deleteProductById);

BRANDS ROUTES....................................... 1- router.get('/getbrandbyname', getBrandByName); 2- router.get('/getallbrands', getAllBrands) 3- router.post('/brands', postBrands); 4- router.delete('/deleteproductsbybrand', deleteProductsByBrand); 5- router.put('/updatebrand/:id', updateBrandById); 6- router.get('/getbrandbyid', getBrandById);

CATEGORY ROUTES......................................... 1- router.post('/categories', postCategories); 2- router.get('/getallcategories', getAllCategories) 3- router.get('/getcategorybyid/:id', getCategoryById); 4- router.get('/getcategorybyname', getCategoryByName); 5- router.put('/updatecategory', updateCategoryById); 6- router.delete('/deleteproductsbycategory', deleteProductsByCategory);

Order ROUTES................................................... 1- router.post('/send-demo-mail', demoMail) 2- router.post('/create-order', addOrders) 3- router.get('/all-orders', allOrders) 4- router.get('/order-by-id/:_id', orderById)
