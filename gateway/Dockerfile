FROM nginx:1.22

COPY nginx.conf /etc/nginx/conf.d/default.conf

COPY --from=frontend-builder /app/build /staticfiles